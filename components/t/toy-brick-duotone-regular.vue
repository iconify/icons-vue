<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q3if5di8r"/><path class="ab48ccc0f"/><path class="u3mqizjgw"/><path class="k311anbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toy-brick-duotone-regular" /></template>
<style>
.ab48ccc0f {
  d: path("M4 9v10h16V9Z");
}

.k311anbdb {
  d: path("M14 9V6h3v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q3if5di8r {
  fill: currentColor;
  d: path("M4 9v10h16V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u3mqizjgw {
  d: path("M7 9V6h3v3");
}

</style>
