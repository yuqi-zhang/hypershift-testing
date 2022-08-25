FROM quay.io/openshift-release-dev/ocp-v4.0-art-dev@sha256:7d39d0f5fe33754167376915ef74c0bd2e8fef6b4584515b3bb91aead8c78904
RUN rpm-ostree install http://download.eng.bos.redhat.com/brewroot/vol/rhel-8/packages/ltrace/0.7.91/28.el8/x86_64/ltrace-0.7.91-28.el8.x86_64.rpm  && \
    rpm-ostree cleanup -m
