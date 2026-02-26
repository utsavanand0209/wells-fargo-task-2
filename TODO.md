# TODO List - Data Model Implementation

## Entities to Create:
1. [x] Client.java - Entity with ManyToOne relationship to Advisor
2. [x] Portfolio.java - Entity with OneToOne relationship to Client (unique)
3. [x] Security.java - Entity with ManyToOne relationship to Portfolio

## Requirements for each entity:
- [x] @Entity annotation from jakarta.persistence
- [x] @Id with @GeneratedValue for auto-generated IDs
- [x] @Column or @OneToOne/@ManyToOne annotations for all fields
- [x] Constructor initializing all instance variables
- [x] Getters for all fields
- [x] Setters for all fields (except ID)

## Existing Entity:
- [x] Advisor.java - Already provided

## Follow-up:
- [ ] Commit and push changes to GitHub

