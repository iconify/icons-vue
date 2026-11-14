<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tcuqj5s4q"/><path class="v06xd9jvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microphone" /></template>
<style>
.tcuqj5s4q {
  d: path("M10 2.5h4a1 1 0 0 1 1 1V13a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v06xd9jvw {
  d: path("M5.5 11a6.5 6.5 0 0 0 13 0M12 17.5v4");
}

</style>
