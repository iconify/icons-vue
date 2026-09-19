<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="phm4gabme"/><path class="dl6-wlbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tata-play" /></template>
<style>
.dl6-wlbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.388 26.052v7.689h4.831M10.75 33.74v-7.688h3.19c1.422 0 2.576 1.156 2.576 2.583s-1.154 2.582-2.577 2.582H10.75m27-5.165l-3.2 3.845l-3.2-3.845m3.2 7.689v-3.844m-8.959 3.821l3.14-7.666l3.14 7.689");
}

.phm4gabme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4m.75-28.241h6.549m-3.274 7.715v-7.715m3.274 7.692l3.212-7.692m3.214 7.715l-3.214-7.715m3.264 0h6.549m-3.275 7.715v-7.715m3.275 7.692l3.211-7.692m3.215 7.715l-3.215-7.715");
}

</style>
