<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n6wnddbkz"/><path class="e_fxkjb3i"/><path class="xk7pyn5tx"/><path class="zwc307_dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ultrasound-duotone-regular" /></template>
<style>
.e_fxkjb3i {
  d: path("M4 3h6v11a3 3 0 0 1 -6 0Z");
}

.n6wnddbkz {
  fill: currentColor;
  d: path("M4 3h6v11a3 3 0 0 1 -6 0Z");
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

.xk7pyn5tx {
  d: path("M13 6a4 4 0 0 1 0 8");
}

.zwc307_dz {
  d: path("M13 3a7 7 0 0 1 0 14");
}

</style>
