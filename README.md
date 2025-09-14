# Analyzing HTTP Traffic with Wireshark

## Introduction

In this project, you'll see how I used Wireshark to capture and analyze HTTP traffic. HTTP traffic analysis is crucial for understanding web communication, identifying potential security issues, and investigating anomalies in network traffic.

## Lab Set-up and Tools

1. **Wireshark**: Downloaded and installed Wireshark from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html).
2. **Web Browser**: Any modern web browser (e.g., Chrome, Firefox) for generating HTTP traffic.

## Exercises

### Exercise 1: Capture HTTP Traffic

#### Steps

1. Opened Wireshark.
2. Selected the network interface that connects to the internet.
3. Clicked on the "Start Capture" button (the blue shark fin icon).
4. Opened my web browser and navigated to a website that uses HTTP (e.g., http://example.com).
5. I let the page load completely and then stopped the capture in Wireshark by clicking on the red square icon.


### Exercise 2: Filter HTTP Traffic

#### Steps

1. In Wireshark, went to the filter bar at the top.
2. Entered the filter `http` and pressed Enter.
3. Wireshark displayed only the HTTP traffic from the capture.


### Exercise 3: Analyze HTTP Requests

#### Steps

1. In the filtered HTTP traffic, located an HTTP GET request.
2. Clicked on the GET request to view its details in the packet details pane.
3. Expanded the "Hypertext Transfer Protocol" section to see detailed information about the request, such as the requested URL, headers, and parameters.


### Exercise 4: Analyze HTTP Responses

#### Steps

1. In the filtered HTTP traffic, located the corresponding HTTP response for the GET request you analyzed.
2. Clicked on the response to view its details in the packet details pane.
3. Expanded the "Hypertext Transfer Protocol" section to see detailed information about the response, such as the status code, headers, and content type.


### Exercise 5: Extract and Examine Payload Data

#### Steps

1. In the HTTP response details, looked for the payload data (e.g., HTML content).
2. Right-clicked on the response packet and selected "Follow" > "TCP Stream" to view the entire HTTP conversation.
3. Examined the payload data in the TCP stream window to understand the content being transferred.


## Conclusion

By completing these exercises, I leaned how to capture, filter, and analyze HTTP traffic using Wireshark. These skills are essential for understanding web communication, troubleshooting network issues, and performing security investigations.
