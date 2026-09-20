<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="f25l9jbma"/><path class="fmjdq2b_j"/><path class="h80pwkurs"/></g><circle class="vu9xg0juq"/><circle class="vb9lx0bzu"/><circle class="j68i6r-4l"/><circle class="np1mw6bkz"/><path class="wpa7_7b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:permission-pilot" /></template>
<style>
.f25l9jbma {
  d: path("M15.666 13.062q-.575.345-1.127.743l-2.181-2.214a2.664 2.664 0 0 0-3.767-.004l-.004.004a2.655 2.655 0 0 0 0 3.746l2.264 2.23a16.2 16.2 0 0 0-3.071 9.456v3.41h32.353v-3.41c.011-3.397-.98-6.712-2.962-9.472l2.273-2.247a2.647 2.647 0 0 0 .002-3.744l-.002-.002a2.647 2.647 0 0 0-3.744-.02l-.019.02l-2.264 2.247a16 16 0 0 0-1.269-.827M17.143 26.393a2.623 2.623 0 1 1 2.616-2.63v.014a2.616 2.616 0 0 1-2.616 2.616h-.014zm13.57.105a2.623 2.623 0 1 1 2.602-2.645v.03a2.616 2.616 0 0 1-2.616 2.615zM7.78 30.52v10.231c0 .966.783 1.749 1.749 1.749h28.855c.962 0 1.749-.787 1.749-1.749V30.433");
}

.fmjdq2b_j {
  d: path("m17.136 30.433l6.82 6.908l6.736-6.908m-6.818-19.549V9.415m-1.247 1.173l-1.974-.855m3.221 3.027c4.345 0 10.415-1.316 10.415-2.72S29.881 5.5 23.874 5.5s-10.415 3.136-10.415 4.54s6.07 2.72 10.415 2.72");
}

.h80pwkurs {
  d: path("M32.238 11.484v1.276c0 .778-4.134 2.675-8.364 2.675s-8.364-1.897-8.364-2.675v-1.277m9.611-.895l1.974-.855m-5.077 20.7l1.251 1.846m2.449 3.192l-1.16-3.192h-1.289l-1.159 3.192m3.699-5.038l-1.251 1.846");
}

.j68i6r-4l {
  cx: 30.692px;
  cy: 35.235px;
  r: 0.75px;
  fill: currentColor;
}

.np1mw6bkz {
  cx: 30.692px;
  cy: 38.543px;
  r: 0.75px;
  fill: currentColor;
}

.vb9lx0bzu {
  cx: 17.136px;
  cy: 38.543px;
  r: 0.75px;
  fill: currentColor;
}

.vu9xg0juq {
  cx: 17.136px;
  cy: 35.235px;
  r: 0.75px;
  fill: currentColor;
}

.wpa7_7b7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.15 33.294h1.177M7.78 34.974a4.54 4.54 0 0 0 4.54-4.54");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
