<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jm8-5lslf"/><circle class="f2yjju4lp"/><path class="j7p47fbty"/></g><g class="y9tr6bcfx"><path class="yass6ubvg"/><path class="iyicr9ynx"/><path class="ta_lxgptt"/><path class="p3om5ebmq"/><path class="ju464ac-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rainbow-kwgt" /></template>
<style>
.f2yjju4lp {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
}

.iyicr9ynx {
  d: path("M42.01 32.432C37.966 26.868 31.405 23.25 24 23.25c-8.075 0-15.145 4.301-19.044 10.738");
}

.j7p47fbty {
  d: path("M36.654 34.492v8.016m3.692 0v-2.053L38.273 38.5l2.073-1.955v-2.053");
}

.jm8-5lslf {
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-2.174 9.431");
}

.ju464ac-k {
  d: path("M44.338 17.013C38.606 12.913 31.585 10.5 24 10.5S9.394 12.913 3.662 17.012");
}

.p3om5ebmq {
  d: path("M45.494 23.51C39.95 18.09 32.365 14.75 24 14.75S8.043 18.093 2.499 23.517");
}

.ta_lxgptt {
  d: path("M44.874 29.172C40.023 22.98 32.476 19 24 19S7.977 22.98 3.127 29.172");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yass6ubvg {
  d: path("M35.906 32A17.93 17.93 0 0 0 24 27.5c-7.25 0-13.498 4.286-16.35 10.461");
}

</style>
