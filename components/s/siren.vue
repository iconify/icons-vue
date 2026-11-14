<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ef0dbc_ei"/><path class="i09avnb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:siren" /></template>
<style>
.ef0dbc_ei {
  d: path("M6.5 17.5V13a5.5 5.5 0 0 1 11 0v4.5m-11.75 0h12.5A1.75 1.75 0 0 1 20 19.25A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i09avnb_o {
  d: path("M9.5 13a2.5 2.5 0 0 1 2.5-2.5m0-8v2M3.5 6L5 7.5M20.5 6L19 7.5");
}

</style>
