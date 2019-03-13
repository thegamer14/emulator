{
#if defined(VC) || defined(CLASSIC)
	const size_t maxCacheSize = 15000;
#elif defined(HAVE_LIBNX)
	const size_t maxCacheSize = 4500;
#else
	const size_t maxCacheSize = 16384;
#endif

