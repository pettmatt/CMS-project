# About

CMS system mind excercise project that might result to something or might not.

## Structure

- Server that powers the CMS
- Database (fast and always accessable)
- General application logic and CMS templates
	- Logic references to the CMS engine, that handles changes and interactions with APIs
	- CMS template/interface needs to also have its own API
- Headless design???
  - If headless then the API needs to be easily accessable and understandable
  - If headless then the template needs to be simple, inclusive and accessable

## Technologies and techniques

Backend:
	- Rust (reliable and modern)
	- Architecture (not specified)

Frontend:
	- Loosely integratable with backend, so the language/tech doesn't really matter if it can make HTTP-requests
	- Design requirements (not specified)

Administration:
	- Should user authentication be the only separator between a normal user and an admin?
		- If yes, the CMS interface might be less manageable
		- If no, how the CMS interfaces should be separated? In different subdomains or paths?
			- Does this even matter at the end of the day, or does this introduce too much complexity?

## Flowchart

## Data structures

## Data flow
