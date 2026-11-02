<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f19qm5bcq"/><path class="xd3b4uwlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-duocolor-sharp" /></template>
<style>
.f19qm5bcq {
  stroke-opacity: 0.4;
  d: path("M12 6H5v4m4-7l3 3l-3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xd3b4uwlw {
  d: path("M5 14v6h14V6h-3");
}

</style>
