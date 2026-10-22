# guidelines.jsmcah.org

Landing page for the evidence sites that accompany ASV guidelines. This repository (`jsmcah/jsmcah.github.io`) owns the domain through its `CNAME` file. Every other public repository in the jsmcah organization is served under the same domain by its name, so `jsmcah/vaccination` appears at guidelines.jsmcah.org/vaccination/.

To add a guideline, create its public repository in the organization, turn on GitHub Pages for it (Settings, Pages, deploy from the `main` branch), and add an entry to `index.html` here. No DNS change is needed.

`robots.txt` here applies to the whole domain, including every guideline. It currently asks search engines not to index anything.

DNS for jsmcah.org is managed outside GitHub. The records this site needs are a CNAME from `guidelines` to `jsmcah.github.io` and GitHub's domain verification TXT record.
