# amazon-clone-practice

A static Amazon sign-in page clone exercise. Open `amazon.html` in a
browser (it links `style.css` in the same folder). No build step, no
JavaScript, no real sign-in — the form does not submit anywhere.

Prepared corrections in this folder:

- `amazon.html` — stylesheet `<link>` moved from `<body>` to `<head>`,
  email field is now `type="email"`, logo image gained an `alt`
  attribute, and bare `&nbsp` entities were corrected to `&nbsp;`.
- `style.css` — fixed the missing semicolon after `width: 98%`,
  corrected the invalid colour `light-grey` to `lightgrey`, and merged
  the duplicate `.create_button` rule into one.
