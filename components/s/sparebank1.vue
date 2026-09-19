<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="q0lj3fb_t"/><path class="bk_4accne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sparebank1" /></template>
<style>
.bk_4accne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.8 36.5V18.8c0-.5-.1-.7-.7-.7h-3.2c-.8 0-1-.3-1-1v-3.2q0-.6.6-.9c2-1 4.1-2.1 6.1-3.1c.5-.3 1-.4 1.6-.4h4.2c1 0 1.2.2 1.2 1.2v22.6");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q0lj3fb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.3 29.6c.1.2.6 1.1.7 1.2c2.2 2.9 5.2 4.6 8.7 5.6c2.6.7 5.3.8 8 .5c1.4-.2 3-.6 4.8-1.3c1-.4 2.5-1 4.1-2c.1-.1 1.6-.9 2.8-2c3.1-2.7 5.3-6.1 6.2-10.1c1-4.7.1-9-3.1-12.7c-2.8-3.3-6.4-4.9-10.5-5.6c-1.9-.3-3.9-.3-5.8 0c-.6.1-1.1.1-1.4.2");
}

</style>
