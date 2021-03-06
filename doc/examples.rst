.. _examples_overview:


Overview of Examples
====================

The examples give an overview of the features of |ab| by providing working code.

Read, run, and modify as you like!

.. note:: Most examples provide HTML clients and/or JavaScript versions of the Python code. JavaScript code for WAMP v2 runs both in the browser and in Node.js.

.. _websocket_examples:

WebSocket
---------

|ab| provides WebSocket both under `Twisted <http://twistedmatrix.com/>`_ and `asyncio <http://docs.python.org/3.4/library/asyncio.html>`_.

Basic Examples
++++++++++++++

 * WebSocket Echo:  `Twisted <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo>`__  - `asyncio <https://github.com/tavendo/AutobahnPython/blob/master/examples/asyncio/websocket/echo>`__
 * Slow Square: `Twisted <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/slowsquare>`__  - `asyncio <https://github.com/tavendo/AutobahnPython/blob/master/examples/asyncio/websocket/slowsquare>`__
 * Testee: `Twisted <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/testee>`__  - `asyncio <https://github.com/tavendo/AutobahnPython/blob/master/examples/asyncio/websocket/testee>`__


Additional Examples (Twisted only)
++++++++++++++++++++++++++++++++++

 * `Broadcasting over WebSocket <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/broadcast>`_
 * `WebSocket Compression <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_compressed>`_
 * `WebSocket over Twisted Endpoints <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_endpoints>`_
 * `Using HTTP Headers with WebSocket <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_httpheaders>`_
 * `WebSocket on Multicore <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_multicore>`_
 * `WebSocket as a Twisted Service <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_service>`_
 * `Running WebSocket under Twisted Web <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_site>`_
 * `Running secure WebSocket under Twisted Web <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_site_tls>`_
 * `WebSocket Echo over secure WebSocket <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_tls>`_
 * `WebSocket Echo Variants <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_variants>`_
 * `WebSocket Fallbacks <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_wsfallbacks>`_
 * `WebSocket and WSGI/Flask <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/echo_wsgi>`_
 * `Using multiple WebSocket Protocols <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/multiproto>`_
 * `WebSocket Pings/Pongs <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/ping>`_
 * `Streaming WebSocket <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/streaming>`_
 * `Wrapping Twisted Protocol/Factories over WebSocket <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/websocket/wrapping>`_



WAMP v2
-------

Publish & Subscribe (PubSub)
++++++++++++++++++++++++++++

 * Basic `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/pubsub/basic>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/pubsub/basic>`__ - Demonstrates basic publish and subscribe.

 * Complex `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/pubsub/complex>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/pubsub/complex>`__ - Demonstrates publish and subscribe with complex events.

 * Options `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/pubsub/options>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/pubsub/options>`__ - Using options with PubSub.

 * Unsubscribe `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/pubsub/unsubscribe>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/pubsub/unsubscribe>`__ - Cancel a subscription to a topic.


Remote Procedure Calls (RPC)
++++++++++++++++++++++++++++

 * Time Service `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/timeservice>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/timeservice>`__ - A trivial time service - demonstrates basic remote procedure feature.

 * Slow Square `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/slowsquare>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/slowsquare>`__ - Demonstrates procedures which return promises and return asynchronously.

 * Arguments `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/arguments>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/arguments>`__ - Demonstrates all variants of call arguments.

 * Complex Result `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/complex>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/complex>`__  - Demonstrates complex call results (call results with more than one positional or keyword results).

 * Errors `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/errors>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/errors>`__ - Demonstrates error raising and catching over remote procedures.

 * Progressive Results `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/progress>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/progress>`__ - Demonstrates calling remote procedures that produce progressive results.

 * Options `Twisted <https://github.com/tavendo/AutobahnPython/tree/master/examples/twisted/wamp/basic/rpc/options>`__ - `asyncio <https://github.com/tavendo/AutobahnPython/tree/master/examples/asyncio/wamp/basic/rpc/options>`__ - Using options with RPC.


WAMP v1
-------

Examples demonstrating specific features:

Publish & Subscribe
+++++++++++++++++++

 * `Basic PubSub 1 <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/pubsub/simple/example1>`_
 * `Basic PubSub 2 <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/pubsub/simple/example2>`_
 * `Custom PubSub Handlers <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/pubsub/custom>`_
 * `Profiling PubSub <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/pubsub/loadlatency>`_

Remote Procedure Calls
++++++++++++++++++++++

 * `Basic RPCs 1 <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/rpc/simple/example1>`_
 * `Basic RPCs 2 <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/rpc/simple/example1>`_
 * `Symmetric RPCs <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/rpc/symmetric>`_
 * `Profiling RPCs <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/rpc/profile>`_

Authentication
++++++++++++++

 * `Authenticating via WAMP-CRA <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/authentication>`_


and small example apps

 * `Decimal Calculator <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/apps/calculator>`_
 * `A Key-Value Store <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/apps/keyvalue>`_
 * `A WAMP-DBus Bridge <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/apps/dbus>`_
 * `A directory watcher <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/apps/dirwatch>`_
 * `Serial/Arduino-to-WAMP Bridge <https://github.com/tavendo/AutobahnPython/blob/master/examples/twisted/wamp1/apps/serial2ws>`_
