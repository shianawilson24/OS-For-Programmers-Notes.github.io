<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>

<h1>Basics of a Computer System</h1>

<h2>CPU (Central Processing Unit)</h2>
<ul>
    <li>Executes machine instructions to perform operations on the contents of registers and memory locations.</li>
</ul>

<h2>RAM (Random Access Memory)</h2>
<ul>
    <li>Linear sequence of addressable bytes or words that hold programs and data.</li>
</ul>

<h2>Secondary Storage</h2>
<ul>
    <li>Disk and other devices with complex sequences of low-level operations to store and access data in discrete blocks.</li>
</ul>

<h2>I/O Devices</h2>
<ul>
    <li>Read and write registers of the device controllers.</li>
</ul>

<h2>Operating System (OS)</h2>

<h3>Definition</h3>
<ul>
    <li>Software that runs on bare hardware, providing essential support for efficient and safe use of applications.</li>
</ul>

<h3>Key Components and Concepts</h3>
<ul>
    <li><strong>Kernel:</strong> The minimal set of functions necessary to manage system resources safely and efficiently.</li>
    <li><strong>Privileged Instructions:</strong> Perform critical operations that access I/O devices and CPU’s status/control registers; only executable by the OS kernel.</li>
    <li><strong>Kernel Mode:</strong> CPU state allowing both privileged and non-privileged instructions.</li>
    <li><strong>User Mode:</strong> CPU state allowing only non-privileged instructions.</li>
    <li><strong>Graphic User Interface (GUI):</strong> Presents icons on the screen for users to invoke services or reveal additional tasks (e.g., website or application).</li>
</ul>

<h2>Multiprogramming and Time Sharing</h2>
<ul>
    <li><strong>Multiprogramming:</strong> Keeps several programs active in memory and switches execution among them to maximize CPU and resource usage.</li>
    <li><strong>Time Sharing (Multitasking):</strong> Extension of multiprogramming where the CPU switches among active computations to guarantee acceptable response times, creating the illusion of separate virtual CPUs for each computation.</li>
</ul>

<h2>Shell Commands and Scripts</h2>
<ul>
    <li><strong>DIR:</strong> Displays a list of files and subdirectories.</li>
    <li><strong>COPY:</strong> Copies files to another location.</li>
    <li><strong>WC:</strong> Counts words, lines, and characters in a text file.</li>
    <li><strong>DEL:</strong> Deletes files.</li>
</ul>

<h3>Shell Script</h3>
<ul>
    <li>Program that combines multiple commands and control statements into a named unit interpreted by the shell.</li>
</ul>

<h2>System Calls and Interrupts</h2>

<h3>System Call</h3>
<ul>
    <li>Request from an application for an OS service, typically implemented by a library function and a corresponding supervisor call.</li>
</ul>

<h3>Supervisor Call (Kernel Call)</h3>
<ul>
    <li>Privileged instruction transferring execution control to a predefined location within the OS kernel.</li>
</ul>

<h3>Interrupt</h3>
<ul>
    <li>Event diverting program execution to a kernel location in response to hardware signals.</li>
</ul>

<h3>Trap</h3>
<ul>
    <li>Internal interrupt triggered by the currently executing instruction.</li>
</ul>

<h3>Interrupt Handler</h3>
<ul>
    <li>Kernel function invoked when an interrupt occurs.</li>
</ul>

<h2>Moore’s Law and Bus</h2>

<h3>Moore’s Law</h3>
<ul>
    <li>Observation that the number of transistors in an integrated circuit doubles approximately every two years.</li>
</ul>

<h3>Bus</h3>
<ul>
    <li>Provides access between components and shared memory in a computer system.</li>
</ul>

<h2>Device Driver and Network Computing</h2>

<h3>Device Driver</h3>
<ul>
    <li>Understands the device controller and provides a uniform interface to the device for the OS.</li>
</ul>

<h3>Network Computers (Thin Clients)</h3>
<ul>
    <li>Terminals for web-based computing, used for security and easier maintenance.</li>
</ul>

<h3>Firewalls</h3>
<ul>
    <li>Used to protect networks from security breaches.</li>
</ul>

<h3>Mobile Computing</h3>
<ul>
    <li>Refers to computing on handheld devices like smartphones and tablets.</li>
</ul>

<h2>Compute and File-Server Systems</h2>

<h3>Compute Server System</h3>
<ul>
    <li>Provides interfaces for clients to send requests to perform actions (e.g., reading data).</li>
</ul>

<h3>File-Server System</h3>
<ul>
    <li>Provides file system interfaces for creating, updating, reading, and deleting files (e.g., web servers).</li>
</ul>

<h3>Cloud Computing</h3>
<ul>
    <li>Delivers computing, storage, and applications as services across a network, using virtualization as a base.</li>
</ul>

<h3>ASICs</h3>
<ul>
    <li>Performs tasks without an operating system.</li>
</ul>

<h2>Historical Generations of Computer Systems</h2>

<h3>Gen 1: Vacuum Tubes</h3>
<ul>
    <li>No OS support; programming done using machine language.</li>
</ul>

<h3>Gen 2: Transistors</h3>
<ul>
    <li>Batch OS; programming with punch cards, introduction of multiprogramming.</li>
</ul>

<h3>Gen 3: Integration Circuits</h3>
<ul>
    <li>Interactive multi-user OS; development of interrupts for time sharing and interaction with peripherals.</li>
</ul>

<h3>Gen 4: VLSI (Very Large Scale Integration)</h3>
<ul>
    <li>Desktop and laptop OS; responsible for booting, multitasking, GUI, etc.</li>
</ul>

<h3>Gen 5: Networking Hardware</h3>
<ul>
    <li>OS for supercomputers, distributed systems, mobile devices; parallel processing, the Internet, privacy, security, and communication.</li>
</ul>

<h2>Client-Server and Peer-to-Peer Systems</h2>

<h3>Client-Server System</h3>
<ul>
    <li>General structure providing services to clients.</li>
</ul>

<h3>Peer-to-Peer (P2P) Computing</h3>
<ul>
    <li>Distributed system model with no centralized service; nodes act as both clients and servers.</li>
    <li>Examples: File-sharing services (Napster, Gnutella), Skype.</li>
</ul>

<h2>Embedded Systems</h2>

<h3>Definition</h3>
<ul>
    <li>Always runs real-time operating systems for specific tasks.</li>
</ul>

<h2>Command Interpreter</h2>

<h3>Definition</h3>
<ul>
    <li>Known as shells, they allow users to enter commands directly to the OS.</li>
</ul>

<h3>Main Function</h3>
<ul>
    <li>Execute user-specified commands.</li>
</ul>

<h3>System Calls Categories</h3>
<ul>
    <li><strong>Process Control:</strong> Create/terminate processes, load/execute, set attributes, etc.</li>
    <li><strong>File Management:</strong> Create/delete, open/close, read/write, set attributes.</li>
    <li><strong>Device Management:</strong> Request/release device, read/write, set attributes.</li>
    <li><strong>Information Maintenance:</strong> Get/set time, system data, attributes.</li>
    <li><strong>Communications:</strong> Create/delete connections, send/receive messages.</li>
    <li><strong>Protection:</strong> Get/set file permissions.</li>
</ul>

</body>
</html>
