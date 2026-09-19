<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y680hoblx"/><path class="dx0uhbc9k"/><path class="m5pg4lbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unseen-gallery" /></template>
<style>
.dx0uhbc9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.703 19.817a4.492 4.492 0 0 0-6.197 4.154c.003.584.12 1.16.344 1.7m2.805 2.584a4.5 4.5 0 0 0 1.344.21a4.492 4.492 0 0 0 4.284-5.84");
}

.m5pg4lbdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.49 17.03a18 18 0 0 0-4.501-.594A17.83 17.83 0 0 0 9.5 23.94a17.8 17.8 0 0 0 6.494 5.585m3.95 1.44a18 18 0 0 0 4.045.48A17.88 17.88 0 0 0 38.5 23.94a17.86 17.86 0 0 0-6.17-5.407");
}

.y680hoblx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.48 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29.04a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4zm5.442 27.512l18.023-18.024");
}

</style>
