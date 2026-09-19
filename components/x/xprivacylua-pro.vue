<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7r0kab9c"/><path class="k2c-wcb6u"/><path class="j-jc7hbei"/><path class="tahgmitpl"/><circle class="s8jx3bcdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xprivacylua-pro" /></template>
<style>
.j-jc7hbei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.238 37.597a17 17 0 0 1-9.683 3.034c-9.519 0-17.235-7.864-17.235-17.566S14.036 5.5 23.555 5.5S40.79 13.364 40.79 23.066h0a17.78 17.78 0 0 1-3.687 10.857");
}

.k2c-wcb6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.867 14.588l-1.974 7.927l-7.938.022");
}

.m7r0kab9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.265 34.286v-4.76h1.6c.922 0 1.66.714 1.66 1.606s-.738 1.607-1.66 1.607h-1.6m7.153-.405c0-.655.554-1.19 1.23-1.19s1.231.535 1.231 1.19v.773c0 .655-.554 1.19-1.23 1.19s-1.231-.535-1.231-1.19zm-2.313-.068c0-.654.554-1.19 1.23-1.19h0m-1.23 0v3.213M8.447 20.749l6.1-6.105l1.437 7.913l8.029-.03l.065-11.005M19.974 37.72l4.164-4.163l-.228-10.848");
}

.s8jx3bcdu {
  cx: 39.092px;
  cy: 39.911px;
  r: 2.589px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tahgmitpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.134 11.471a14 14 0 0 0 7.534 3.052c.73.063 1.463.067 2.19.012");
}

</style>
