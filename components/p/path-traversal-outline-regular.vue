<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bn_pu6j-z"/><path class="ri_favbdz"/><path class="nyd87ccoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:path-traversal-outline-regular" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nyd87ccoj {
  d: path("M9.5 16.5 12 14l2.5 2.5");
}

.ri_favbdz {
  d: path("M9.5 12.5 12 10l2.5 2.5");
}

</style>
