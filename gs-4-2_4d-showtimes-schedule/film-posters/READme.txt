Folder structure:

/web/

	- Only optimized, signage-ready images
	- These are what your CMS and signage will reference

/archive/

	- Optional
	- Store original SimEx assets (large 2000×2889 files)
	- Not referenced by the site

---

Naming convention for /web/ ...

[film-slug]_poster_[size].jpg

	- Example:
		turtle-odyssey-4d_poster_sm.jpg
		shark-experience-4d_poster_sm.jpg

If we ever introduce multiple sizes:

		turtle-odyssey-4d_poster_sm.jpg
		turtle-odyssey-4d_poster_md.jpg
		turtle-odyssey-4d_poster_lg.jpg

---

🔗 URL Pattern (what goes into Supabase)

Store this in films.poster_url:

	/gs-5-2_4d-showtimes-schedule/film-posters/web/turtle-odyssey-4d_poster_sm.jpg

Or absolute (preferred for signage reliability):

	https://vaq-mattdobo.github.io/exhibits-dept/gs-5-2_4d-showtimes-schedule/film-posters/web/turtle-odyssey-4d_poster_sm.jpg