<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clyy6mbyw"/><path class="gk5iptbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supervpn" /></template>
<style>
.clyy6mbyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.693 0 15.274-7.782 15.274-16.966V6.504C35.267 6.503 24 4.5 24 4.5S12.723 6.503 8.727 6.503v20.03C8.727 35.719 22.307 43.5 24 43.5");
}

.gk5iptbct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.705 27.637c1.043 1.357 2.35 1.863 4.169 1.863h2.516a4.24 4.24 0 0 0 4.241-4.24v-.02a4.24 4.24 0 0 0-4.24-4.24h-2.777a4.245 4.245 0 0 1-4.245-4.245h0a4.255 4.255 0 0 1 4.254-4.255h2.503c1.82 0 3.126.506 4.169 1.863");
}

</style>
