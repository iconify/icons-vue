<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eu2k7mbls"/><path class="ck2v-d7fm"/><path class="nk-ya7nyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sonos" /></template>
<style>
.ck2v-d7fm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.47 20.8a3.26 3.26 0 0 0-2.39-.65h-.65M6.69 27.2a3.24 3.24 0 0 0 2.39.65h.65m28.54-7.7a1.92 1.92 0 0 0-1.92 1.93A1.92 1.92 0 0 0 38.27 24h.65m0 0h.65a1.92 1.92 0 0 1 1.92 1.92a1.92 1.92 0 0 1-1.92 1.93m1.74-7.05a3.24 3.24 0 0 0-2.39-.65h-.65m-1.74 7.05a3.26 3.26 0 0 0 2.39.65h.65");
}

.eu2k7mbls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.12 22.73a2.57 2.57 0 0 0-2.72-2.57a2.67 2.67 0 0 0-2.4 2.72v2.39a2.58 2.58 0 0 0 2.58 2.57a2.58 2.58 0 0 0 2.58-2.57v-2.54m14.84 0a2.57 2.57 0 0 0-2.72-2.57a2.67 2.67 0 0 0-2.44 2.72v2.39a2.58 2.58 0 0 0 2.58 2.57A2.58 2.58 0 0 0 34 25.27zm-12.58-2.57v7.68m5.16 0v-7.68m-5.16 0l5.16 7.68M8.43 20.15a1.92 1.92 0 0 0-1.92 1.93A1.92 1.92 0 0 0 8.43 24h.65m0 0h.65a1.92 1.92 0 0 1 1.92 1.92a1.92 1.92 0 0 1-1.92 1.93");
}

.nk-ya7nyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.44 21.44 0 0 0 24 2.5");
}

</style>
