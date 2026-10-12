<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="idt6wnbmf"/><circle class="ptvu1u_4n"/><path class="drg1ibcqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medal-ribbon" /></template>
<style>
.drg1ibcqg {
  d: path("M8 15.5h2.25q.5 0 .44.5l-.63 4.75q-.06.5-.38.12l-.61-.74q-.32-.38-.7-.05l-.99.84q-.38.33-.34-.17L7.46 16q.04-.5.54-.5m5.75 0H16q.5 0 .54.5l.42 4.75q.04.5-.34.17l-.99-.84q-.38-.33-.7.05l-.61.74q-.32.38-.38-.12L13.31 16q-.06-.5.44-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idt6wnbmf {
  d: path("M12.56 3.27zq.57.53 1.32.36q.75-.18.97.56q.23.73.96.96q.74.23.56.97q-.17.75.36 1.32q.52.56 0 1.12q-.53.57-.36 1.32q.18.75-.56.97q-.73.23-.96.96q-.22.74-.97.56q-.75-.17-1.32.36q-.56.52-1.12 0q-.57-.53-1.32-.36q-.74.18-.97-.56q-.23-.73-.96-.96q-.74-.22-.56-.97q.17-.75-.36-1.32q-.52-.56 0-1.12q.53-.57.36-1.32q-.18-.74.56-.97q.73-.23.96-.96q.22-.74.97-.56q.75.17 1.32-.36q.56-.52 1.12 0");
}

.ptvu1u_4n {
  cx: 12px;
  cy: 8px;
  r: 2px;
}

</style>
