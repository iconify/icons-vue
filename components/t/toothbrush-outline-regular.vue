<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qrdwmtbvi"/><path class="w6zihnbcy"/><path class="vrecxx6kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toothbrush-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrdwmtbvi {
  d: path("M9 3h6v7H9Z");
}

.vrecxx6kh {
  d: path("M9 6h6");
}

.w6zihnbcy {
  d: path("M12 10v11");
}

</style>
