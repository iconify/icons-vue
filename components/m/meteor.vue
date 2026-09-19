<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nyh815yds"/><path class="qw17kvb6w"/><circle class="rgewmhbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meteor" /></template>
<style>
.nyh815yds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.543 27.472h-7.872a1.736 1.736 0 0 0 0 3.471h13.886a6.943 6.943 0 0 0 0-13.886H5.236a1.736 1.736 0 0 0 0 3.472h6.145");
}

.qw17kvb6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.547 20.529H11.381a1.736 1.736 0 0 0 0 3.471h6.145m13.088 0H17.526a1.736 1.736 0 0 0 0 3.472h6.145");
}

.rgewmhbbb {
  cx: 37.557px;
  cy: 24px;
  r: 3.739px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
