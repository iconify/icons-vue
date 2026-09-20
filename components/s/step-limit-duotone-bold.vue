<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qte4s3bkt"/><path class="h0-l53bzw"/><path class="v8t37dedd"/><path class="gg6jr8oaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-limit-duotone-bold" /></template>
<style>
.gg6jr8oaf {
  d: path("M21 4v16");
}

.h0-l53bzw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qte4s3bkt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h5v5h5v5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v8t37dedd {
  d: path("M3 6h5v5h5v5h5");
}

</style>
