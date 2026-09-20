<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qx76d9rce"/><path class="qrdwmtbvi"/><path class="w6zihnbcy"/><path class="vrecxx6kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toothbrush-duotone-bold" /></template>
<style>
.qrdwmtbvi {
  d: path("M9 3h6v7H9Z");
}

.qx76d9rce {
  fill: currentColor;
  d: path("M9 3h6v7H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vrecxx6kh {
  d: path("M9 6h6");
}

.w6zihnbcy {
  d: path("M12 10v11");
}

</style>
