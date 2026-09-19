<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0b7x4bkm"/><path class="a8zau9ble"/><path class="u5dwpsbvq"/><path class="bjlgugb5b"/><path class="b6jh60vyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sstv-encoder" /></template>
<style>
.a8zau9ble {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.07c17.007.82 30.61 14.423 31.43 31.43");
}

.b6jh60vyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.501 27.802a16.366 16.366 0 0 1 14.697 14.696M5.502 33.407c4.7.7 8.39 4.39 9.09 9.09M5.503 39.8A4.58 4.58 0 0 1 8.2 42.497");
}

.bjlgugb5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 22.218c10.857.79 19.492 9.423 20.282 20.28");
}

.n0b7x4bkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5c20.082.828 36.172 16.918 37 37");
}

.u5dwpsbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.501 16.642c13.932.808 25.05 11.925 25.857 25.857");
}

</style>
