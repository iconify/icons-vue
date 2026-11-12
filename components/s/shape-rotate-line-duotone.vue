<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vxow8dbzk"/><path class="ge6g5hbyr"/><path class="r84d1mxrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shape-rotate-line-duotone" /></template>
<style>
.ge6g5hbyr {
  stroke-linejoin: round;
  d: path("M20.5 6.986L22 8C22 4.9853 19.8377 2.4828 17 2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r84d1mxrv {
  stroke-linejoin: round;
  d: path("M3.5 17.014L2 16C2 19.0147 4.1623 21.5172 7 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vxow8dbzk {
  d: path("M4.8778 5.5561L5.5561 4.8778C7.4746 2.9593 8.4339 2 9.6259 2C10.818 2 11.7772 2.9593 13.6958 4.8778L19.1222 10.3042C21.0407 12.2228 22 13.182 22 14.3741C22 15.5661 21.0407 16.5254 19.1222 18.4439L18.4439 19.1222C16.5254 21.0407 15.5661 22 14.3741 22C13.182 22 12.2228 21.0407 10.3042 19.1222L4.8778 13.6958C2.9593 11.7772 2 10.818 2 9.6259C2 8.4339 2.9593 7.4746 4.8778 5.5561Z");
}

</style>
