<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lgiv6v-yu"/><path class="a_ebczbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-duocolor" /></template>
<style>
.a_ebczbfm {
  d: path("M3 21h18M5 21V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16m-9 0v-2a2 2 0 1 1 4 0v2");
}

.lgiv6v-yu {
  stroke-opacity: 0.4;
  d: path("m12 6.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
