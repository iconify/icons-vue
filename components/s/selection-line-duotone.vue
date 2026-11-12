<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ucndu_bux"/><path class="f5b5c9bje"/><path class="tn2zr5pbo"/><path class="baqv_u95v"/><path class="eu306zbbi"/><path class="d4tgdxbtn"/><path class="dr570wbqr"/><path class="dlpuuib8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:selection-line-duotone" /></template>
<style>
.baqv_u95v {
  d: path("M22 20C22 21.1046 21.1046 22 20 22C18.8954 22 18 21.1046 18 20C18 18.8954 18.8954 18 20 18C21.1046 18 22 18.8954 22 20Z");
}

.d4tgdxbtn {
  d: path("M18 4H6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.dlpuuib8p {
  d: path("M4 6V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.dr570wbqr {
  d: path("M20 18V6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.eu306zbbi {
  d: path("M6 20H18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f5b5c9bje {
  d: path("M6 20C6 21.1046 5.1046 22 4 22C2.8954 22 2 21.1046 2 20C2 18.8954 2.8954 18 4 18C5.1046 18 6 18.8954 6 20Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tn2zr5pbo {
  d: path("M22 4C22 5.1046 21.1046 6 20 6C18.8954 6 18 5.1046 18 4C18 2.8954 18.8954 2 20 2C21.1046 2 22 2.8954 22 4Z");
}

.ucndu_bux {
  d: path("M6 4C6 5.1046 5.1046 6 4 6C2.8954 6 2 5.1046 2 4C2 2.8954 2.8954 2 4 2C5.1046 2 6 2.8954 6 4Z");
}

</style>
