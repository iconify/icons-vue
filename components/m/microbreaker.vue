<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v4ag074de"/><path class="mb7zczbyd"/><path class="zcximoboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microbreaker" /></template>
<style>
.mb7zczbyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.483 23.089l-2.111-5.951l14.915-1.364l2.488 7.032l2.714 7.657l-7.438.685m2.235-15.378l-14.917 1.366l12.015-8.235L37.3 7.536z");
}

.v4ag074de {
  cx: 14.285px;
  cy: 31.679px;
  r: 8.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zcximoboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.486 30.46L42.5 22.226l-5.2-14.69l-12.014 8.234zm-9.378-4.31a2.45 2.45 0 0 0 1.753-2.585a2.44 2.44 0 0 0-2.666-2.196a2.436 2.436 0 0 0-2.206 2.354m4.849-.401l4.939-.516m12.203-7.7l-12.203 7.7");
}

</style>
