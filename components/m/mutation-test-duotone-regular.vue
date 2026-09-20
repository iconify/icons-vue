<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b1gzncccy"/><path class="mkh6f026t"/><path class="s0wwcab9o"/><path class="a5dy0ccpe"/><path class="dtpuy8bcg"/><path class="k6nj2fbya"/><path class="pesxdybze"/><path class="s4ceatb9m"/><path class="f8057zb1p"/><path class="xqeoz9oav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mutation-test-duotone-regular" /></template>
<style>
.a5dy0ccpe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b1gzncccy {
  fill: currentColor;
  d: path("M13 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dtpuy8bcg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 17 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f8057zb1p {
  d: path("M18 12h3");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pesxdybze {
  d: path("M3 12h7");
}

.s0wwcab9o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s4ceatb9m {
  d: path("M13 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xqeoz9oav {
  d: path("m9 17 2 2 4 -4");
}

</style>
