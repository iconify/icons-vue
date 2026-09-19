<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzau8nbgn"/><path class="qjd_9mrbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pinterest" /></template>
<style>
.mzau8nbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 44.23s5.36-22.32 5.89-23.72c-5.12.49-3.48 12.49 2.32 13.8c4.91 1.15 10.35-4.54 10.27-10.85S31.69 14 27 12.69s-12.15.31-14.13 6.87a10.53 10.53 0 0 0 3 11.47");
}

.qjd_9mrbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.51 21.51 0 0 0 24 2.5");
}

</style>
