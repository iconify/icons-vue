<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="akyaa-boy"/><path class="nuk2gwb4b"/><path class="gstzuxb9r"/><path class="ldq326b0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trumpet-outline-regular" /></template>
<style>
.akyaa-boy {
  d: path("M13 11H2v4h11");
}

.gstzuxb9r {
  d: path("M5 7v4");
}

.ldq326b0y {
  d: path("M9 7v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuk2gwb4b {
  d: path("m13 9 6 -6v18l-6 -6Z");
}

</style>
