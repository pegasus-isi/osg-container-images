FROM opensciencegrid/osgvo-el7

MAINTAINER Mats Rynge <rynge@isi.edu>

# make sure we have a stashcp in the path
RUN ln -f -s /cvmfs/oasis.opensciencegrid.org/osg/modules/stashcp/5.1.2/bin/stashcp /usr/bin/stashcp

# build info
RUN echo "Timestamp:" `date --utc` | tee /image-build-info.txt

