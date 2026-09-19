<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yo71l7h4h"/><path class="kuce5ibgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mindfulnotifier" /></template>
<style>
.kuce5ibgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.721 29.76c8.467 0 15.221 2.367 15.221 5.19v7.264H5.5V34.95c0-2.823 6.753-5.19 15.221-5.19M32.974 9.702a14.79 14.79 0 0 1 0 16.523M38.78 5.786a21.8 21.8 0 0 1 0 24.355");
}

.yo71l7h4h {
  cx: 20.721px;
  cy: 17.963px;
  r: 7.611px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
