<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d3xn50bni"/><path class="j9d013d3m"/><path class="t6wnch_5a"/><path class="wlia6bb5b"/><path class="ml9nf9zke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:packing-list-outline-regular" /></template>
<style>
.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.j9d013d3m {
  d: path("M9 2v20");
}

.ml9nf9zke {
  d: path("m11 16 2 2 3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t6wnch_5a {
  d: path("m11 7 2 2 3 -3");
}

.wlia6bb5b {
  d: path("M11 12h7");
}

</style>
