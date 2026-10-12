<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ruxy7k6qn"/><path class="uro4albms"/><path class="cfjx_i05i"/><circle class="dwvbaw88m"/><circle class="iblfxcc2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trojan-horse-sharp" /></template>
<style>
.cfjx_i05i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 15.5h15v2.75h-15z");
}

.dwvbaw88m {
  cx: 7.5px;
  cy: 19.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iblfxcc2h {
  cx: 16.5px;
  cy: 19.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ruxy7k6qn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 15.5V10c0-3.6 2.4-6.4 5.75-7L14 4.5l3.6 3.4l.971.971L17.8 9.9l-.55.75l-.828 1.104l-1.072-.804L13.5 9.5v6Z");
}

.uro4albms {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 6.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
