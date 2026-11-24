<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wm7sp8bqj"/><path class="a_ebczbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-duocolor" /></template>
<style>
.a_ebczbfm {
  d: path("M3 21h18M5 21V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16m-9 0v-2a2 2 0 1 1 4 0v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wm7sp8bqj {
  stroke-opacity: 0.4;
  d: path("M12 6h2.25a.75.75 0 0 1 .75.75v1.875c0 2.063-1.312 3.375-3 4.125c-1.687-.75-3-2.062-3-4.125V6.75A.75.75 0 0 1 9.75 6z");
}

</style>
