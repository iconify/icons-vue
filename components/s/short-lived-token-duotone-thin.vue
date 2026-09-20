<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-vxqtmbe"/><path class="t7fcj43nv"/><path class="b2a9_acks"/><path class="ziznm1ama"/><path class="ny9m1pboy"/><path class="yaetm9cyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:short-lived-token-duotone-thin" /></template>
<style>
.b-vxqtmbe {
  fill: currentColor;
  d: path("M2 12a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.b2a9_acks {
  d: path("M2 12a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ny9m1pboy {
  d: path("M18 9.5V12");
}

.t7fcj43nv {
  fill: currentColor;
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yaetm9cyz {
  d: path("M18 12h2.5");
}

.ziznm1ama {
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
