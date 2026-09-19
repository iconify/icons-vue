<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><g class="y9tr6bcfx"><path class="ms_n3zb-v"/><path class="v1-9jlbuc"/></g><g class="y9tr6bcfx"><path class="johu5lb5m"/><path class="pfc3qxxgr"/></g><path class="s8xjrfbzw"/><ellipse class="a9nsk_gjd"/>`;
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

.johu5lb5m {
  d: path("M18.042 13.315c0-.912.74-1.651 1.651-1.651h0c.912 0 1.652.74 1.652 1.651v2.724m-3.303-4.375v4.376");
}

.ms_n3zb-v {
  d: path("M29.958 14.388v2.23c0 .911-.74 1.65-1.651 1.65h0c-.456 0-.87-.184-1.168-.483");
}

.pfc3qxxgr {
  d: path("M21.345 13.315a1.65 1.65 0 0 1 1.65-1.651h0c.913 0 1.652.74 1.652 1.651v2.724");
}

.s8xjrfbzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.073 31.311v-6.747l3.377 6.754l3.377-6.743v6.743m8.338 0v-6.754l4.474 6.754v-6.754m-10.82 0h4.474m-2.237 6.754v-6.754");
}

.v1-9jlbuc {
  d: path("M29.958 11.664v2.724c0 .912-.74 1.652-1.651 1.652h0c-.912 0-1.652-.74-1.652-1.652v-2.724");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
