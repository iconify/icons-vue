<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jbq3dzslw"/><path class="d1k_xlftc"/><circle class="bar3ntbmm"/><path class="qlodqzbve"/><circle class="wijmr5spd"/><path class="ua_p3lzyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:standup-meeting" /></template>
<style>
.bar3ntbmm {
  cx: 17.5px;
  cy: 13px;
  r: 2.25px;
}

.d1k_xlftc {
  d: path("M3.5 21.25h6a.75.75 0 0 0 .75-.75c0-1.9-1.65-3-3.75-3s-3.75 1.1-3.75 3a.75.75 0 0 0 .75.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbq3dzslw {
  cx: 6.5px;
  cy: 13px;
  r: 2.25px;
}

.qlodqzbve {
  d: path("M14.5 21.25h6a.75.75 0 0 0 .75-.75c0-1.9-1.65-3-3.75-3s-3.75 1.1-3.75 3a.75.75 0 0 0 .75.75");
}

.ua_p3lzyk {
  d: path("M12 4.25v1.5l1.25 1");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

</style>
