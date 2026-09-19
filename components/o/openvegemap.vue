<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s1615ibwt"/><circle class="zhgwgdq2g"/><path class="auup-xuza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openvegemap" /></template>
<style>
.auup-xuza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.266 14.645a2.09 2.09 0 0 1 1.051-1.703c.994-.673 1.725-.423 2.054-.072a1.64 1.64 0 0 1 .091 1.966c-.73 1.061-1.72.673-2.42 1.665c-1.89 2.679-2.955 4.384-3.485 8.049v.001l-1.16-5s-.918-4.672-3.86-6.775");
}

.s1615ibwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.502a13.09 13.09 0 0 0-13.09 13.09c0 10.25 10 22.61 12.61 25.63a.8.8 0 0 0 1.21 0c2.55-3 12.36-15.38 12.36-25.63A13.09 13.09 0 0 0 24 4.502");
}

.zhgwgdq2g {
  cx: 24.004px;
  cy: 17.596px;
  r: 10.09px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
