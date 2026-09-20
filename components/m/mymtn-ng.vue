<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><g class="y9tr6bcfx"><path class="k9ku3x_zo"/><path class="mfkbfyjry"/></g><path class="zdppz5x7n"/><ellipse class="a9nsk_gjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymtn-ng" /></template>
<style>
.a9nsk_gjd {
  cx: 24px;
  cy: 27.941px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 15px;
  ry: 7.395px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.k9ku3x_zo {
  d: path("M29.958 14.388v2.23a1.651 1.651 0 0 1-2.819 1.167");
}

.mfkbfyjry {
  d: path("M29.958 11.664v2.724a1.651 1.651 0 1 1-3.302 0v-2.724");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zdppz5x7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.042 13.315a1.651 1.651 0 0 1 3.302 0v2.724m-3.302-4.375v4.376m3.303-2.725a1.651 1.651 0 0 1 3.302 0v2.724M14.073 31.311v-6.747l3.377 6.754l3.377-6.743v6.743m8.338 0v-6.754l4.474 6.754v-6.754m-10.82 0h4.474m-2.237 6.754v-6.754");
}

</style>
