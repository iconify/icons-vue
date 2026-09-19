<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="xqkbb0g9m"/><path class="f3kdg3b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sendreducedfree" /></template>
<style>
.f3kdg3b1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M11.63 17.17h24.74M11.63 4.5h24.74m-24.74 6.37h24.74M27.21 43.5a7 7 0 0 0-6.42 0m9.21-6a14 14 0 0 0-12 0m14.66-5.75a20.69 20.69 0 0 0-17.32 0");
}

.xqkbb0g9m {
  cx: 24px;
  cy: 23.54px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  rx: 13px;
  ry: 2.77px;
}

</style>
