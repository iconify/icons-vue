<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="skhsrsbjf"/><path class="aky9nc-vf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zakat-coin" /></template>
<style>
.aky9nc-vf {
  d: path("M13.55 5.2a1.4 1.4 0 1 0 0 2.6a1.5 1.5 0 0 1 0-2.6m-10.8 9.3H6l3 1.75h3.5a1.25 1.25 0 0 1 0 2.5H9.25M14.5 18l4.25-2.25a1.4 1.4 0 0 1 1.75 2.2l-5.5 3.3H6.5L2.75 20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.skhsrsbjf {
  cx: 13px;
  cy: 6.5px;
  r: 3.75px;
}

</style>
