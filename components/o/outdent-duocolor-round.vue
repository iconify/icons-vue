<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f4vji8emu"/><path class="i3xzrim4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:outdent-duocolor-round" /></template>
<style>
.f4vji8emu {
  stroke-opacity: 0.4;
  d: path("m8 8l-4 4l4 4");
}

.i3xzrim4g {
  d: path("M12 6h8m-8 4h8m-8 4h8m-8 4h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
