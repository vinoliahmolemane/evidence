# evidence
The media failed because the rescue service was looking in a container called cloud03-media-missing, but my files are in cloud03-media. The image request failed with [HTTP 503, if your output showed that] while the health check still said 200. After I recreated only the rescue container with the correct name, the image and video both loaded (HTTP 200) and my main site stayed working
