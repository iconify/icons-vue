<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dlydupbcg"/><rect transform="rotate(45 24 17.625)" class="fu026acxa"/><rect transform="rotate(45 30.375 24)" class="ypj348y3r"/><rect transform="rotate(45 17.626 24)" class="srj1x3bku"/><rect transform="rotate(45 24 30.375)" class="ewtkh6bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:you-icon-pack" /></template>
<style>
.dlydupbcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.862 27.17c-2.727 3.25 1.182 7.11-4.247 9.506c-3.985 1.451-2.53 6.749-8.43 6.11c-4.177-.736-5.566 4.578-10.355 1.076c-3.25-2.727-7.11 1.182-9.506-4.247c-1.451-3.985-6.748-2.53-6.11-8.43C5.952 27.008.637 25.62 4.14 20.83c2.726-3.25-1.182-7.11 4.246-9.506c3.985-1.451 2.53-6.748 8.43-6.11C20.992 5.952 22.38.637 27.17 4.14c3.25 2.726 7.11-1.182 9.506 4.246c1.451 3.985 6.748 2.53 6.11 8.43c-.737 4.177 4.578 5.566 1.076 10.355");
}

.ewtkh6bqu {
  width: 6.01px;
  height: 6.01px;
  x: 20.995px;
  y: 27.369px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.fu026acxa {
  width: 6.01px;
  height: 6.01px;
  x: 20.995px;
  y: 14.62px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.srj1x3bku {
  width: 6.01px;
  height: 6.01px;
  x: 14.62px;
  y: 20.995px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.ypj348y3r {
  width: 6.01px;
  height: 6.01px;
  x: 27.369px;
  y: 20.995px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
