<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w96h5_xzz"/><circle class="upiqu7bqs"/><path class="ha2t1qbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subtune" /></template>
<style>
.ha2t1qbxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.032 31.254l-.003-9.077l4.59 4.645c1.433 1.449 1.005 3.951-.56 5.259");
}

.upiqu7bqs {
  cx: 22.038px;
  cy: 33.523px;
  r: 3.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w96h5_xzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.323 22.924c0-8.674 7.032-15.705 15.705-15.705s15.706 7.031 15.706 15.705m-25.985.988l.053 14.87H7.72c-1.137 0-2.219-.516-2.219-1.575V26.1c0-1.172.875-2.189 1.922-2.189zm20.422 0l-.053 14.87h6.46c.976 0 1.922-.592 1.922-1.549V26.021c0-1.055-.618-2.109-1.682-2.109zm5.563-.988v.988m-31.411-.988v.988");
}

</style>
