<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="neoa7xerr"/><circle class="fsznv8biv"/><circle class="ca1383bdq"/><path class="r_feo74gf"/><circle class="p_2-nnb5d"/><circle class="thuoocb4m"/><path class="mnrk6gcal"/><circle class="qs8962udv"/><circle class="nvtoinbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pipes" /></template>
<style>
.ca1383bdq {
  cx: 6.565px;
  cy: 6.222px;
  r: 0.75px;
  fill: currentColor;
}

.fsznv8biv {
  cx: 24.361px;
  cy: 32.89px;
  r: 0.75px;
  fill: currentColor;
}

.mnrk6gcal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.565 39.525V37.33m0 0V18.838c0-2.066 1.71-3.728 3.836-3.728h.614l2.223-.01");
}

.neoa7xerr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.79 6.219l2.224.003h9.488c2.138 0 3.86 1.66 3.86 3.72v1.244c0 2.172 1.716 3.92 3.848 3.92h.595l.596-.002c2.138 0 3.858 1.661 3.858 3.726v10.134c0 2.174-1.716 3.924-3.848 3.924h-.608l-2.217-.023");
}

.nvtoinbtp {
  cx: 15.463px;
  cy: 15.111px;
  r: 0.75px;
  fill: currentColor;
}

.p_2-nnb5d {
  cx: 24.361px;
  cy: 23.999px;
  r: 0.75px;
  fill: currentColor;
}

.qs8962udv {
  cx: 6.565px;
  cy: 41.778px;
  r: 0.75px;
  fill: currentColor;
}

.r_feo74gf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.484 6.219l2.224.003h.613c2.125 0 3.836 1.663 3.836 3.727v27.902c0 2.175-1.716 3.925-3.848 3.925H19.298c-2.125 0-3.835-1.749-3.835-3.922V27.72c0-2.06 1.721-3.72 3.859-3.72h.604l2.21-.017");
}

.thuoocb4m {
  cx: 33.26px;
  cy: 6.222px;
  r: 0.75px;
  fill: currentColor;
}

</style>
