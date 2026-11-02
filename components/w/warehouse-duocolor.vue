<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ygr-3532s"/><path class="hb0kq9b2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-duocolor" /></template>
<style>
.hb0kq9b2t {
  d: path("M3 21h18M5 21V11c0-.613.774-1.387 2-2l4-2h2l4 2c1.226.613 2 1.387 2 2v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ygr-3532s {
  stroke-opacity: 0.4;
  d: path("M9 21v-8h6v8m-6-4h6");
}

</style>
