<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j54dk3bwa"/><path class="navy19bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meditation-timer-and-log" /></template>
<style>
.j54dk3bwa {
  cx: 29.585px;
  cy: 25.137px;
  r: 5.635px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.navy19bly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.22 25.137c0-8.501-5.239-11.17-9.885-11.17s-11.368 2.372-11.368 11.17s4.448 14.827 15.619 14.827c10.577 0 15.915-8.303 15.915-14.827C45.5 18.909 44.577 2.5 24.18 2.5C6.553 2.5 2.5 17.92 2.5 25.137a30.08 30.08 0 0 0 7.513 18.386");
}

</style>
