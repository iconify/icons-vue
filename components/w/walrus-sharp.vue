<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xt-qmkydk"/><path class="pnyzhrb6l"/><path class="j-1tgnb-q"/><path class="dxzhv-zcp"/><path class="kz30hnxkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:walrus-sharp" /></template>
<style>
.dxzhv-zcp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.5h.01m4.49 0h.01");
}

.j-1tgnb-q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 11l1-1h1.25a2.5 2.5 0 0 1 0 5H13l-1-1l-1 1H9.75a2.5 2.5 0 0 1 0-5H11z");
}

.kz30hnxkh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15v4m4.5-4v4");
}

.pnyzhrb6l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 7.5h.01m4.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xt-qmkydk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5c-1.25 1.25-1.75 3.25-1.75 5.25v2h16.5v-2c0-2-.5-4-1.75-5.25M12 5c4.25 0 7.25 2.25 7.25 5.25V13H4.75v-2.75c0-3 3-5.25 7.25-5.25Z");
}

</style>
