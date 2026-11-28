<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="izjqynbzi"/><path class="yr5z-vu-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-plus-two-tone" /></template>
<style>
.izjqynbzi {
  stroke-opacity: 0.4;
  d: path("M3 8V6C3 4.34315 4.34315 3 6 3H8M16 3H18C19.6569 3 21 4.34315 21 6V8M8 21H6C4.34315 21 3 19.6569 3 18V16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yr5z-vu-e {
  d: path("M18 15L18 21M15 18L21 18");
}

</style>
