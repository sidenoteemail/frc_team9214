# arena_bringup/docs

## Run docker container

`docker run -d -p 8080:8080 plantuml/plantuml-server:jetty`

## Generate PlantUML diagrams

`plantuml team9214_ws/src/arena_bringup/docs/bringup_nodes_topics.puml`
`plantuml team9214_ws/src/arena_bringup/docs/bringup_single_cam_nodes_topics.puml`
`plantuml team9214_ws/src/arena_bringup/docs/bringup_multi_cam_nodes_topics.puml`

## Generate SVGs with Docker Compose

From this directory:

`docker compose run --rm plantuml`
