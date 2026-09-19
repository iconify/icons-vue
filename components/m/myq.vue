<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="en3pnmb2b"/><g class="y9tr6bcfx"><path class="bhid48blh"/><path class="ph22vlb0u"/></g><path class="stxg3f4yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myq" /></template>
<style>
.bhid48blh {
  d: path("M28.748 25.086v3.912c0 1.6-1.297 2.897-2.898 2.897h0c-.8 0-1.524-.324-2.048-.849");
}

.en3pnmb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 22.914c0-1.6 1.297-2.898 2.897-2.898h0c1.6 0 2.897 1.297 2.897 2.897v4.78M9.5 20.016v7.678m5.794-4.78c0-1.6 1.297-2.898 2.898-2.898h0c1.6 0 2.897 1.297 2.897 2.897v4.78");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ph22vlb0u {
  d: path("M28.748 20.306v4.78c0 1.6-1.297 2.898-2.898 2.898h0a2.897 2.897 0 0 1-2.897-2.897v-4.78");
}

.stxg3f4yd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.5 27.694l-3.839-3.793m0-7.796a3.84 3.84 0 0 1 3.839 3.839v3.911a3.84 3.84 0 0 1-3.839 3.839h0a3.84 3.84 0 0 1-3.839-3.839v-3.911a3.84 3.84 0 0 1 3.84-3.839");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
