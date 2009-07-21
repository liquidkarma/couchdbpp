lib_LTLIBRARIES = libcouchdb++.la
libcouchdb___la_SOURCES  = Attachment.cpp Communication.cpp Connection.cpp Database.cpp Document.cpp Exception.cpp Revision.cpp
libcouchdb___la_CXXFLAGS = -Wall -I$(VPATH)/../include $(CURL_CFLAGS) $(BOOST_CPPFLAGS)
libcouchdb___la_LDFLAGS  = $(CURL_LIBS)

nobase_include_HEADERS = $(VPATH)/../include/couchdb/Attachment.hpp $(VPATH)/../include/couchdb/Communication.hpp $(VPATH)/../include/couchdb/Connection.hpp $(VPATH)/../include/couchdb/CouchDB.hpp $(VPATH)/../include/couchdb/Database.hpp $(VPATH)/../include/couchdb/Document.hpp $(VPATH)/../include/couchdb/Exception.hpp $(VPATH)/../include/couchdb/Revision.hpp
