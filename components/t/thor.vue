<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="da5b_rbzk"/><ellipse class="mdttxw_xd"/><path class="r3bfdcbhb"/><path class="yjm1qhb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thor" /></template>
<style>
.da5b_rbzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 22.19v-1.383h6.387v1.383m-3.194-1.383v6.067m-1.277.319h2.555m4.258-6.386h1.383v6.067H16.23M17.612 24h4.684m1.384-3.193h-1.384v6.067h1.384");
}

.mdttxw_xd {
  cx: 28.736px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.3px;
  ry: 2.981px;
}

.r3bfdcbhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.024 27.193v-6.067m-1.278 0H38.4c2.096 0 2.006 2.98 0 2.98h-3.376m2.815 0l1.597 3.087H40.5m-6.54 0h2.554");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
