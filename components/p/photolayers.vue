<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iohechbpe"/><path class="nw4dzfb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photolayers" /></template>
<style>
.iohechbpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.459 15.692l4.395-7.6h0L42.5 16.534L31.169 36.13l-6.628-3.82");
}

.nw4dzfb8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.831 11.871l14.647 8.442l-11.332 19.595L5.5 31.466z");
}

</style>
