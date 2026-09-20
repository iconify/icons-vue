<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzeve79sx"/><path class="sru-6bb3w"/><path class="f8-w18bfe"/><path class="ok9mgmb9o"/><path class="yhxg0gb1u"/><path class="ifnz35boy"/><path class="wp14ejvwu"/><path class="ymw3aibdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trampoline-duotone-regular" /></template>
<style>
.f8-w18bfe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ifnz35boy {
  d: path("M5 12v8");
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ok9mgmb9o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sru-6bb3w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11c4 3 14 3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wp14ejvwu {
  d: path("M19 12v8");
}

.yhxg0gb1u {
  d: path("M3 11c4 3 14 3 18 0");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
