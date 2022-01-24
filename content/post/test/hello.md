---
title: "Hello"
date: 2022-01-24T17:54:55+08:00
tags: ["a","b","c"]
categories: ["redis","git"]
draft: false
---

## hello world

```java
	private URL getCleanedUrl(URL originalUrl, String originalPath) {
		String cleanedPath = StringUtils.cleanPath(originalPath);
		if (!cleanedPath.equals(originalPath)) {
			try {
				return new URL(cleanedPath);
			}
			catch (MalformedURLException ex) {
				// Cleaned URL path cannot be converted to URL -> take original URL.
			}
		}
		return originalUrl;
	}

```

