<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3ijmobdd"/><path class="zgxuderfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-merge-duocolor-sharp" /></template>
<style>
.n3ijmobdd {
  stroke-opacity: 0.4;
  d: path("M12 4v5m0 6v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zgxuderfk {
  d: path("M4 4h16v16H4Zm0 5h16M4 15h16");
}

</style>
