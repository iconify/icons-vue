<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a517a_nqs"/><path class="as6fsnbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-cone-duocolor-sharp" /></template>
<style>
.a517a_nqs {
  stroke-opacity: 0.4;
  d: path("M9 10h6m-8 5h10");
}

.as6fsnbrg {
  d: path("m5 20l6-15h2l6 15M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
