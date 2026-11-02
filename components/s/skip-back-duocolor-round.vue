<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7pjc2b7b"/><path class="tb5ooiqfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tb5ooiqfe {
  d: path("m15.336 5.504l-6 4c-1.781 1.187-1.781 3.805 0 4.992l6 4C17.33 19.826 20 18.396 20 16V8c0-2.396-2.67-3.825-4.664-2.496");
}

.u7pjc2b7b {
  stroke-opacity: 0.4;
  d: path("M4 5v14");
}

</style>
