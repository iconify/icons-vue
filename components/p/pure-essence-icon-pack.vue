<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7ydx-bgm"/><path class="m26r1-bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pure-essence-icon-pack" /></template>
<style>
.f7ydx-bgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.588 41.193L19.28 42.5H6.5a1 1 0 0 1-1-1V28.72L28.72 5.5H41.5a1 1 0 0 1 1 1v12.78L28.104 33.678M7.126 20.907L5.5 19.28V6.5a1 1 0 0 1 1-1h12.78l1.627 1.626");
}

.m26r1-bfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.874 27.093L42.5 28.72V41.5a1 1 0 0 1-1 1H28.72L13.311 27.093");
}

</style>
