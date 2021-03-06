
.. Licensed to the Apache Software Foundation (ASF) under one or more
   contributor license agreements.  See the NOTICE file distributed
   with this work for additional information regarding copyright
   ownership.  The ASF licenses this file to you under the Apache
   License, Version 2.0 (the "License"); you may not use this file
   except in compliance with the License.  You may obtain a copy of
   the License at

   http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
   implied.  See the License for the specific language governing
   permissions and limitations under the License.

.. include:: ../../../common.defs

TSEvent
*******

Synopsis
========

`#include <ts/apidefs.h>`

.. c:type:: TSEvent

Enum typedef defining the possible events which may be passed to a continuation
callback.

Enumeration Members
===================

.. c:macro:: TS_EVENT_NONE

.. c:macro:: TS_EVENT_IMMEDIATE

.. c:macro:: TS_EVENT_TIMEOUT

.. c:macro:: TS_EVENT_ERROR

.. c:macro:: TS_EVENT_CONTINUE

.. c:macro:: TS_EVENT_VCONN_READ_READY

.. c:macro:: TS_EVENT_VCONN_WRITE_READY

.. c:macro:: TS_EVENT_VCONN_READ_COMPLETE

.. c:macro:: TS_EVENT_VCONN_WRITE_COMPLETE

.. c:macro:: TS_EVENT_VCONN_EOS

.. c:macro:: TS_EVENT_VCONN_INACTIVITY_TIMEOUT

.. c:macro:: TS_EVENT_VCONN_ACTIVE_TIMEOUT

.. c:macro:: TS_EVENT_NET_CONNECT

.. c:macro:: TS_EVENT_NET_CONNECT_FAILED

.. c:macro:: TS_EVENT_NET_ACCEPT

.. c:macro:: TS_EVENT_NET_ACCEPT_FAILED

.. c:macro:: TS_EVENT_INTERNAL_206

.. c:macro:: TS_EVENT_INTERNAL_207

.. c:macro:: TS_EVENT_INTERNAL_208

.. c:macro:: TS_EVENT_INTERNAL_209

.. c:macro:: TS_EVENT_INTERNAL_210

.. c:macro:: TS_EVENT_INTERNAL_211

.. c:macro:: TS_EVENT_INTERNAL_212

.. c:macro:: TS_EVENT_HOST_LOOKUP

.. c:macro:: TS_EVENT_CACHE_OPEN_READ

.. c:macro:: TS_EVENT_CACHE_OPEN_READ_FAILED

.. c:macro:: TS_EVENT_CACHE_OPEN_WRITE

.. c:macro:: TS_EVENT_CACHE_OPEN_WRITE_FAILED

.. c:macro:: TS_EVENT_CACHE_REMOVE

.. c:macro:: TS_EVENT_CACHE_REMOVE_FAILED

.. c:macro:: TS_EVENT_CACHE_SCAN

.. c:macro:: TS_EVENT_CACHE_SCAN_FAILED

.. c:macro:: TS_EVENT_CACHE_SCAN_OBJECT

.. c:macro:: TS_EVENT_CACHE_SCAN_OPERATION_BLOCKED

.. c:macro:: TS_EVENT_CACHE_SCAN_OPERATION_FAILED

.. c:macro:: TS_EVENT_CACHE_SCAN_DONE

.. c:macro:: TS_EVENT_CACHE_LOOKUP

.. c:macro:: TS_EVENT_CACHE_READ

.. c:macro:: TS_EVENT_CACHE_DELETE

.. c:macro:: TS_EVENT_CACHE_WRITE

.. c:macro:: TS_EVENT_CACHE_WRITE_HEADER

.. c:macro:: TS_EVENT_CACHE_CLOSE

.. c:macro:: TS_EVENT_CACHE_LOOKUP_READY

.. c:macro:: TS_EVENT_CACHE_LOOKUP_COMPLETE

.. c:macro:: TS_EVENT_CACHE_READ_READY

.. c:macro:: TS_EVENT_CACHE_READ_COMPLETE

.. c:macro:: TS_EVENT_INTERNAL_1200

.. c:macro:: TS_AIO_EVENT_DONE

.. c:macro:: TS_EVENT_HTTP_CONTINUE

.. c:macro:: TS_EVENT_HTTP_ERROR

.. c:macro:: TS_EVENT_HTTP_READ_REQUEST_HDR

.. c:macro:: TS_EVENT_HTTP_OS_DNS

.. c:macro:: TS_EVENT_HTTP_SEND_REQUEST_HDR

.. c:macro:: TS_EVENT_HTTP_READ_CACHE_HDR

.. c:macro:: TS_EVENT_HTTP_READ_RESPONSE_HDR

.. c:macro:: TS_EVENT_HTTP_SEND_RESPONSE_HDR

.. c:macro:: TS_EVENT_HTTP_REQUEST_TRANSFORM

.. c:macro:: TS_EVENT_HTTP_RESPONSE_TRANSFORM

.. c:macro:: TS_EVENT_HTTP_SELECT_ALT

.. c:macro:: TS_EVENT_HTTP_TXN_START

.. c:macro:: TS_EVENT_HTTP_TXN_CLOSE

.. c:macro:: TS_EVENT_HTTP_SSN_START

.. c:macro:: TS_EVENT_HTTP_SSN_CLOSE

.. c:macro:: TS_EVENT_HTTP_CACHE_LOOKUP_COMPLETE

.. c:macro:: TS_EVENT_HTTP_PRE_REMAP

.. c:macro:: TS_EVENT_HTTP_POST_REMAP

.. c:macro:: TS_EVENT_LIFECYCLE_PORTS_INITIALIZED

.. c:macro:: TS_EVENT_LIFECYCLE_PORTS_READY

.. c:macro:: TS_EVENT_LIFECYCLE_CACHE_READY

.. c:macro:: TS_EVENT_LIFECYCLE_MSG

.. c:macro:: TS_EVENT_LIFECYCLE_SERVER_SSL_CTX_INITIALIZED

.. c:macro:: TS_EVENT_LIFECYCLE_CLIENT_SSL_CTX_INITIALIZED

.. c:macro:: TS_EVENT_VCONN_PRE_ACCEPT

.. c:macro:: TS_EVENT_MGMT_UPDATE

.. c:macro:: TS_EVENT_INTERNAL_60200

.. c:macro:: TS_EVENT_INTERNAL_60201

.. c:macro:: TS_EVENT_INTERNAL_60202

Description
===========
