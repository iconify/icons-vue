<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="echu4gtqs"/><path class="icp673bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:payment-message-outline-thin" /></template>
<style>
.echu4gtqs {
  d: path("M7.5 10.5a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.hbdbg_bcy {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icp673bbo {
  d: path("M12 9v3");
}

.lyjarcbwz {
  d: path("M7 18v3l3 -3");
}

</style>
