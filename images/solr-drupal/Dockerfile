ARG SOLR_MAJ_MIN_VERSION
ARG IMAGE_REPO
FROM ${IMAGE_REPO:-lagoon}/solr:${SOLR_MAJ_MIN_VERSION}
ARG SOLR_MAJ_MIN_VERSION

COPY solr${SOLR_MAJ_MIN_VERSION} /solr-conf

CMD ["solr-precreate", "drupal", "/solr-conf"]
