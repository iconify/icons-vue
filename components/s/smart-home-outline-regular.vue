<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p6ibjbc2t"/><path class="fqjbkn2kp"/><path class="it8-m-z-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smart-home-outline-regular" /></template>
<style>
.fqjbkn2kp {
  d: path("M8 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.it8-m-z-e {
  d: path("M19 9c2 3 2 7 0 10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6ibjbc2t {
  d: path("M3 20v-8l7 -7 7 7v8Z");
}

</style>
