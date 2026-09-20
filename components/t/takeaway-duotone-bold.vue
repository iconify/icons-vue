<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e8698-bge"/><path class="gd3gqxb-h"/><path class="bkfy3c96t"/><path class="hjqc4kbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:takeaway-duotone-bold" /></template>
<style>
.bkfy3c96t {
  d: path("m6 11 3 -3h6l3 3");
}

.e8698-bge {
  fill: currentColor;
  d: path("M6 11v9h12v-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gd3gqxb-h {
  d: path("M6 11v9h12v-9Z");
}

.hjqc4kbvp {
  d: path("M10 8a2 2 0 0 1 4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
