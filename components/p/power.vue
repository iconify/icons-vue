<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jnu-pfs9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:power" /></template>
<style>
.jnu-pfs9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.408V19.81m5.255-7.944A13.22 13.22 0 0 1 37.223 24h0c0 7.303-5.92 13.223-13.223 13.223h0c-7.303 0-13.223-5.92-13.223-13.223h0c0-5.27 3.129-10.037 7.964-12.133M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
