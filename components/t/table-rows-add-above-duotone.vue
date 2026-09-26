<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qn4j5jb3u"/><path class="q5571yuok"/><path class="fi-58rber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-add-above-duotone" /></template>
<style>
.fi-58rber {
  d: path("M12 2L12 8M9 5L15 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5571yuok {
  fill: currentColor;
  d: path("M2 12L22 12L22 19C22 21.2091 20.2091 23 18 23L6 23C3.7909 23 2 21.2091 2 19L2 12Z");
  stroke: none;
}

.qn4j5jb3u {
  stroke-opacity: 0.4;
  d: path("M5 4.1716C3.8014 4.5954 3 5.7287 3 7L3 13M21 13L21 7C21 5.7287 20.1986 4.5954 19 4.1716");
}

</style>
