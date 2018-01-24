FROM centos

MAINTAINER Sveta Kotleta <sveta@svetakotleta.ru>

RUN yum -y install gcc make cmake \
                   rpm-build \
                   perl perl-core \
                   vim git;
RUN yum -y install epel-release;
RUN yum -y install cpanspec.noarch;
RUN yum -y install perl-Module-Install \
                   perl-Test-Pod \
                   perl-Test-Pod-Content \
                   perl-Test-Pod-Coverage \
                   perl-XML-LibXML \
                   perl-Types-Serialiser ;

CMD sh -i
