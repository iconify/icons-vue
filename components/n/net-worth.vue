<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kulgnybwf"/><path class="q6nmskbau"/><circle class="wlpeuackt"/><path class="j6d26cc2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:net-worth" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6d26cc2i {
  d: path("M18.88 8.02c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

.kulgnybwf {
  cx: 8.75px;
  cy: 7.5px;
  r: 3.75px;
}

.q6nmskbau {
  d: path("M3.75 20.25h10a1 1 0 0 0 1-1c0-2.9-2.6-5-6-5s-6 2.1-6 5a1 1 0 0 0 1 1");
}

.wlpeuackt {
  cx: 17.75px;
  cy: 9px;
  r: 3.25px;
}

</style>
