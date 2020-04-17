This repository replicates a Kotlin bug where a child project's definitions are generated in the root project.

The definitions for `:child` are at:
`./build/js/packages/kotlin-root-typescript-defs-child/kotlin/kotlin-root-typescript-defs-child.d.ts`
after a build, not inside of the `child/build` folder.
