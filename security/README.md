Security
========

A guide for practicing safe web.

Think
-----

Security is important, and you can't practice these guidelines without
understanding them. Make sure you understand each guideline, why it exists, and
how to follow it.

Failing to follow these guidelines will likely put you, your team, and your
deployed services at risk of compromise or loss of privacy.

Using Passwords
---------------

* Use a unique password for every account you create.
* Use a tool like [pwgen](https://github.com/jbernard/pwgen) or
  [1password](https://agilebits.com/onepassword) to generate random passwords.

Accepting Passwords
-------------------

* Don't store passwords in plain text.
* Don't hash passwords using a reversible cipher.
* Don't hash passwords using a broken cipher, such as MD5 or SHA1.
* Don't accept passwords over HTTP.

HTTPS
-----

* Use HTTPS for all web traffic.
* Use HTTPS in the beginning; it's harder to introduce later.
* Use HTTPS redirects for HTTP traffic.
* Use [HSTS](http://tools.ietf.org/html/rfc6797) headers to enforce HTTPS
  traffic.
* Use secure cookies.
* Avoid protocol-relative URLs.
