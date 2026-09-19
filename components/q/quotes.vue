<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="qkcs6ubbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quotes" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qkcs6ubbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.428 28.711a2.356 2.356 0 0 1-2.356-2.355v-1.531a2.356 2.356 0 1 1 4.711 0v1.53a2.356 2.356 0 0 1-2.356 2.356m-8.997-6.242v3.887a2.356 2.356 0 1 0 4.71 0v-3.887m0 3.887v2.355m18.582-.526c.43.36.894.526 1.937.526h.529a1.56 1.56 0 0 0 0-3.121H39.13a1.56 1.56 0 0 1-1.558-1.56h0a1.56 1.56 0 0 1 1.558-1.561h.528c1.043 0 1.507.165 1.938.526m-13.302-2.469v8.185m-1.237-6.242h2.473m5.79 5.053a2.355 2.355 0 0 1-4.402-1.166v-1.531a2.356 2.356 0 1 1 4.711 0v.765h-4.711m-18.42 3.121l-3.122-3.083m0 3.083a3.12 3.12 0 0 1-3.12-3.121v-3.18a3.121 3.121 0 1 1 6.242 0v3.18a3.12 3.12 0 0 1-3.122 3.121");
}

</style>
