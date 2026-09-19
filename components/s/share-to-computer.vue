<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfx859b7t"/><circle class="h-7uhqsjc"/><circle class="y7g863bas"/><circle class="og08xc82e"/><path class="v8qgiubfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:share-to-computer" /></template>
<style>
.h-7uhqsjc {
  cx: 16.161px;
  cy: 27.425px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.og08xc82e {
  cx: 32.476px;
  cy: 33.085px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v8qgiubfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.443 20.59l-9.224 5.133m.321 2.613l9.65 3.543");
}

.vfx859b7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m4 5.079h-37M10.51 5.5v5.079M15.518 5.5v5.079M20.429 5.5v5.079");
}

.y7g863bas {
  cx: 31.462px;
  cy: 18.819px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
