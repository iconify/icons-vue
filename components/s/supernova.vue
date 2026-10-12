<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fq4t-hpga"/><circle class="ons53cb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:supernova" /></template>
<style>
.fq4t-hpga {
  d: path("m12.23 3.3l1.45 3.53q.23.55.79.32l3.52-1.46q.55-.23.32.32l-1.46 3.52q-.23.56.32.79l3.53 1.45q.55.23 0 .46l-3.53 1.45q-.55.23-.32.79l1.46 3.52q.23.55-.32.32l-3.52-1.46q-.56-.23-.79.32l-1.45 3.53q-.23.55-.46 0l-1.45-3.53q-.23-.55-.79-.32l-3.52 1.46q-.55.23-.32-.32l1.46-3.52q.23-.56-.32-.79L3.3 12.23q-.55-.23 0-.46l3.53-1.45q.55-.23.32-.79L5.69 6.01q-.23-.55.32-.32l3.52 1.46q.56.23.79-.32l1.45-3.53q.23-.55.46 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

</style>
