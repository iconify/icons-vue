<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x112q1bbb"/><path class="wi_a85ble"/><path class="r9sju-e6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:receiptmanager" /></template>
<style>
.r9sju-e6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.6 32.8h2.6V10.6h23.7v27.3c0 3.9-5.4 4.1-5.4 0v-5.1z");
}

.wi_a85ble {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.6 5.3v27.5H6.5V39c0 1.8 2 4.5 4.1 4.5h26a5.19 5.19 0 0 0 4.9-4.9V5.3l-2.3 2.4l-3-3.2l-3.1 3.2l-3-3.2L27 7.7l-3-3.2l-3 3.2l-3.1-3.2l-3.1 3.2Z");
}

.x112q1bbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.7 14.4h10.7v2.7H18.7zm0 6.1h10.7v2.7H18.7zm14.1-6.1h2.6v2.7h-2.6zm0 6.1h2.6v2.7h-2.6z");
}

</style>
