<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qulxcwewf"/><path class="h0cy2s2lo"/><ellipse transform="rotate(-23.234 27.209 11.277)" class="bopwy-buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reboot" /></template>
<style>
.bopwy-buj {
  cx: 27.209px;
  cy: 11.277px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.526px;
  ry: 2.901px;
}

.h0cy2s2lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.828 25.544q-.116-.194-.227-.39a10.116 10.116 0 0 0 12.213 1.375a12.97 12.97 0 0 0 4.395-4.986c1.264 1.47 1.639 3.94 1.898 5.863a10.17 10.17 0 0 1-.879 5.67q-.2.42-.43.823c-1.445 2.533-3.601 4.605-5.04 7.142a15 15 0 0 0-1.424 3.46a17.66 17.66 0 0 1 3.955-13.638q.117-.139.237-.275a10.35 10.35 0 0 1-8.172.589a12.67 12.67 0 0 1-6.333-5.32q-.098-.155-.192-.312Z");
}

.qulxcwewf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.55 34.318c1.79-2.404 6.18-7.911 5.816-13.324c0 0-.06-.886-.071-1.482a18 18 0 0 1 4.104-11.707a13.08 13.08 0 0 0-7.725 9.103l-.05.238a21.25 21.25 0 0 1-13.29-12.931q-.126-.355-.238-.715a18 18 0 0 0 1.483 6.435a22.5 22.5 0 0 0 5.103 7.486c1.301 1.175 3.288 2.887 4.527 4.121");
}

</style>
