<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i211t9xib"/><path class="xfs8wlfhn"/><path class="iml3cbclx"/><path class="kvu524b1m"/><path class="o81w35jwy"/><path class="yu9v0ekyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:open-cors-duotone-bold" /></template>
<style>
.i211t9xib {
  fill: currentColor;
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iml3cbclx {
  d: path("M8 7a4 4 0 0 1 8 0");
}

.kvu524b1m {
  d: path("M7 15.5h10");
}

.o81w35jwy {
  d: path("M9.5 13 7 15.5 9.5 18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xfs8wlfhn {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.yu9v0ekyz {
  d: path("m14.5 13 2.5 2.5 -2.5 2.5");
}

</style>
