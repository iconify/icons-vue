<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bn_pu6j-z"/><path class="hlxwfib3h"/><path class="b4gzso3dl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:purpose-limitation-outline-regular" /></template>
<style>
.b4gzso3dl {
  d: path("M12 13.5v3");
}

.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.hlxwfib3h {
  d: path("m9 10.5 3 3 3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
