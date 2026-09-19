<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="j46kd9bzo"/><path class="ja2r08r6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:matome-reader" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.j46kd9bzo {
  cx: 11.5px;
  cy: 11.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ja2r08r6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.994 24.125c0-.789.666-1.428 1.487-1.428s1.488.64 1.488 1.428v2.356m-2.975-3.784v3.784m2.975-2.356c0-.789.666-1.428 1.488-1.428c.821 0 1.487.64 1.487 1.428v2.356m4.463-1.428c0 .789-.666 1.428-1.488 1.428c-.821 0-1.487-.64-1.487-1.428v-.928c0-.789.666-1.428 1.487-1.428s1.488.639 1.488 1.428m0 2.356v-3.784m2.269-1.178v4.249c0 .394.333.714.744.714h.223m-1.748-3.785h1.562m1.673 1.428c0-.789.666-1.428 1.488-1.428s1.487.64 1.487 1.428v.928c0 .789-.666 1.428-1.487 1.428s-1.488-.639-1.488-1.428zm4.463 0c0-.789.666-1.428 1.488-1.428c.821 0 1.487.64 1.487 1.428v2.356m-2.975-3.784v3.784m2.975-2.356c0-.789.666-1.428 1.488-1.428s1.487.64 1.487 1.428v2.356m4.268-.72a1.5 1.5 0 0 1-1.293.72c-.821 0-1.487-.639-1.487-1.427v-.929c0-.788.666-1.428 1.487-1.428s1.488.64 1.488 1.428v.464h-2.975");
}

</style>
