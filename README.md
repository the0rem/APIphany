# APIphany
PHP API package

### Mission Statement
- Translate legacy code into APIs
 - Annotations/Decorators (Doc Block Hints) to define general configuration
- Easy APIs with minimal config
- Pluggable & extendable
- Composer package (Not a framework)
- PSR-0 to PSR-7 compliant
- Encourage code documentation
- Encourage best pratice
- PHP 5.4+ support 

#### Required Components
- Routing
- Documentation (browsable, auto-generated)
- Versioning (header based)
- Logging (with [Monolog](https://github.com/Seldaek/monolog))
- Authentication/Authorisation (possibly using [Sentinel](https://github.com/cartalyst/sentinel))
- Validation
- Caching
- Throttling
- Exceptions (handle returning correct status codes with custom messages etc)

#### Return types
- JSON
- XML
- YAML
- HTTP (for documentation)
 
#### Backends
- Eloquent Models
- Proxy
- Methods/Functions

### Notes
- Consider [GuzzleHTTP](http://guzzle.readthedocs.org/en/latest/)
