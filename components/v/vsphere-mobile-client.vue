<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f4l-0ubin"/><circle class="xpic3gbna"/><path class="uafjj7gcb"/><circle class="yc094tbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vsphere-mobile-client" /></template>
<style>
.f4l-0ubin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.564 17.32V7.128A2.636 2.636 0 0 0 28.936 4.5H11.843a2.636 2.636 0 0 0-2.628 2.628v33.744a2.636 2.636 0 0 0 2.628 2.628h17.093a2.636 2.636 0 0 0 2.628-2.628v-1.694");
}

.uafjj7gcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.785 39.423l-3.653-4.296M18.057 8.037h4.666M11.966 18.106h3.144l1.62 2.996l2.113-6.877l1.277 3.881h2.848");
}

.xpic3gbna {
  cx: 30.037px;
  cy: 28.361px;
  r: 8.473px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yc094tbhk {
  cx: 20.39px;
  cy: 39.718px;
  r: 1.174px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
