<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkaoopb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nanoloop" /></template>
<style>
.bkaoopb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 22.792H7.124M3.5 25.207h37.376m-30.259 2.416h26.56M17.78 30.04h15.893m-8.859 2.416h5.251m7.318-12.08h-26.56M30.22 17.96H14.327m8.859-2.416h-5.251");
}

</style>
