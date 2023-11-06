function FindProxyForURL(url, host) {
    // Domains to route through the proxy server
    if (shExpMatch(host, "kadellabs.online") ||
        shExpMatch(host, "instagram.com")) {
        return "PROXY 184.72.136.197:3128";
    }
    // All other domains use a direct connection
    return "DIRECT";
}
