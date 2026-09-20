<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gd3gqxb-h"/><path class="bkfy3c96t"/><path class="hjqc4kbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:takeaway-outline-regular" /></template>
<style>
.bkfy3c96t {
  d: path("m6 11 3 -3h6l3 3");
}

.gd3gqxb-h {
  d: path("M6 11v9h12v-9Z");
}

.hjqc4kbvp {
  d: path("M10 8a2 2 0 0 1 4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
