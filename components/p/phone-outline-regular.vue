<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yysxkyxdb"/><path class="sgqi5uicf"/><path class="kk7jzcbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:phone-outline-regular" /></template>
<style>
.kk7jzcbcv {
  d: path("M10 19h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sgqi5uicf {
  d: path("M10 5h4");
}

.yysxkyxdb {
  d: path("M7 4a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
