<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uax7j3gsp"/><path class="x0mx6shao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uax7j3gsp {
  stroke-opacity: 0.4;
  d: path("M20 5v14");
}

.x0mx6shao {
  d: path("m8.664 5.504l6 4c1.781 1.187 1.781 3.805 0 4.992l-6 4C6.67 19.826 4 18.396 4 16V8c0-2.396 2.67-3.825 4.664-2.496");
}

</style>
