This is an attempt to understand why <res.json(posts.map(post=>post.serialize()));> on line 140 of server.js results in errors.

This was to help Hozefa Bharmal figure out why a 'author' is undefined on line 35 of model.js

  return `${this.author.firstName} ${this.author.lastName}`.trim();

Everything above is related.

