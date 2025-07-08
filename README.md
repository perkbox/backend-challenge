# Perkbox Backend Challenge

Welcome to the Perkbox Backend Challenge!

At Perkbox, our systems must securely and efficiently manage thousands of users across a diverse range of businesses.
We value scalable, robust, and maintainable solutions that deliver real value to our customers.

This coding challenge is designed to reflect a real product need at Perkbox.
We want to see how you approach engineering problems such as data modeling, API design, security, and scalability.

Please spend no more than **2-3 hours** on this challenge and focus on delivering clear, thoughtful code that demonstrates your skills.

## The Challenge: User Management Service

Build a service to manage users within Perkbox, where each user belongs to a business.
For this challenge, assume that another service manages businesses - use a made-up `business_id` when associating users.

You are free to choose any API style you prefer (REST, GraphQL, or gRPC).

### Product Requirements

The service should allow:

- **Admins** can create and delete users within their business.
- **Admins** can create and delete other admins within their business.
- **Admins** can list all users within in their business.
- **Users** can update their own details.
- **Anyone** within a business can get the details of another user in the same business by ID.

#### User Fields

Each user should have at least the following fields:
- `id` (unique identifier)
- `business_id` (identifier of the business the user belongs to)
- `name`
- `email` (must be unique within a business)

You are welcome to add more fields if you wish.

### Database Requirements

- You must use a database to persist user data.
- You may use any database technology.
- Document any setup required to initialize the database.

### Getting Started

You can use any frameworks and libraries you are comfortable with.

Please include setup instructions in your repository so we can run your service locally.

## Submission

Please submit your solution as a link to a public repository (GitHub, GitLab, etc.). Your repository should include:

- **README.md** with:
  - Setup instructions
- Source code

**Time-box your effort!** We don’t expect a production-ready system. Focus on clarity and demonstrating your skills.

Good luck! We look forward to seeing your solution.
