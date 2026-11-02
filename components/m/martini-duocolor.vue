<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w6e_frnyg"/><path class="xmbcclbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:martini-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w6e_frnyg {
  stroke-opacity: 0.4;
  d: path("M7 6h10");
}

.xmbcclbqu {
  d: path("M12 11L5 4c-.369-.369.262-1 1-1h12c.738 0 1.369.631 1 1zm0 0v10m-4 0h8");
}

</style>
