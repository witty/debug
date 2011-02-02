## Debug Class

default, all exception and error will handled by this class. you can stop through config

	// enable exception and error handler
	Witty::instance('Debug');
	// disable exception and error handler
	Witty::instance('Debug', array('debug' => FALSE));

### basic usage

	Debug::dump($val1, $val2, ...);
