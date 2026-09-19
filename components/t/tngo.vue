<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zgsudrv8k"/><path class="bit_82b6l"/><circle class="nzayl3szg"/></g><path class="vv92oebdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tngo" /></template>
<style>
.bit_82b6l {
  d: path("M14.25 23.505a2.052 2.052 0 1 1-2.053 0l1.027 1.778zm21.553-.172a2.052 2.052 0 1 1-2.052 0l1.026 1.777z");
}

.nzayl3szg {
  cx: 34.777px;
  cy: 25.282px;
  r: 8.723px;
}

.vv92oebdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.667 19.84l5.774-3.334m7.001-2.256h6.667m-28.221-.256h6.668");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zgsudrv8k {
  d: path("M20.778 20.92a8.723 8.723 0 1 1-3.193-3.192");
}

</style>
