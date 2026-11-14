<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aa0eed8vo"/><path class="ijsygiyzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mushroom-spotted" /></template>
<style>
.aa0eed8vo {
  d: path("M2.5 13C2.5 7 6.75 3 12 3s9.5 4 9.5 10Zm6.25 0v6.5a1.5 1.5 0 0 0 1.5 1.5h3.5a1.5 1.5 0 0 0 1.5-1.5V13");
}

.ijsygiyzm {
  fill: currentColor;
  d: path("M6.5 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
