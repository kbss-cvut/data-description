# Data Description Ontology Change Log

## 2.0.0 - 2026-06-16
- IRIs are based on English names
- major revisions in ontology concepts, removed Glossary and Model, Vocabulary is now subclass of bot skos:ConceptScheme and owl:Ontology
- descriptions of concepts are still missing

## 1.0.9 - 2024-07-18
- Remove pdp:term, replace with skos:Concept if neccesaary

## 1.0.8 - 2023-07-27
- Add a class representing the state of a term and a property referencing it (range skos:Concept)

## 1.0.7 - 2022-06-08
- Add new classes and properties describing snapshots of terms and vocabularies, and relations between them.
