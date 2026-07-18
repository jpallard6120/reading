# Reading

This repository is a record of what I have read, what I thought about it, and what those reactions imply for future recommendations.

The prose is the source of truth. Ratings and metadata are useful shortcuts, but they should never replace the reasons a book worked or failed.

## Repository map

```text
reading/
├── README.md
├── taste-profile.md
├── books/
│   └── README.md
├── recommendations/
│   ├── queue.md
│   └── rejected-or-deferred.md
└── templates/
    └── book-review.md
```

## How to use this repository

1. Create one file in `books/` after finishing or abandoning a book.
2. Record the specific reactions that matter, including mixed or contradictory ones.
3. State what the book teaches us about future recommendations.
4. Update `taste-profile.md` only when a reaction adds meaningful evidence or changes an earlier conclusion.
5. Keep upcoming books in `recommendations/queue.md`. Move books that are ruled out or postponed indefinitely to `recommendations/rejected-or-deferred.md`.

## File conventions

- Use lowercase kebab-case filenames, such as `project-hail-mary.md`.
- Use one file per novel. A whole series may use one file when the reaction applies chiefly to the series as a whole.
- Preserve the reader's own language when possible. A sharp sentence is better evidence than a polished generalization.
- Use `status` values of `finished`, `abandoned`, or `reading`.
- Ratings are optional and may use whatever scale best reflects the original judgment.
- Risks in the queue should describe the likeliest reason a recommendation may miss.

## Recommendation prompt

When asking for a new recommendation, a useful starting prompt is:

> Read `taste-profile.md`, the completed-book reviews, and the current recommendation queue. Recommend one book. Explain which prior reactions support the choice, identify the largest risk of a miss, and do not rely on genre or ratings alone.

