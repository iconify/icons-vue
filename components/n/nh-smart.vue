<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5hec9bgc"/><path class="yrcfe0bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nh-smart" /></template>
<style>
.a5hec9bgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.263 29.353h8.418a2.15 2.15 0 0 1 2.15 2.15v4.246M18.263 17.325h8.418a2.15 2.15 0 0 1 2.15 2.15v4.246m-10.568-2.573h5.797l-5.797 5.423H32.91");
}

.yrcfe0bqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.265 4.5c7.706 0 17.176 9.059 17.176 25.588c0 10.118-7.706 13.412-16.47 13.412c-8.708 0-22.412-5.647-22.412-15.647S15.618 4.5 26.265 4.5");
}

</style>
