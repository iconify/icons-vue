<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpsqs2btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vignette-sharp" /></template>
<style>
.gpsqs2btq {
  fill: currentColor;
  d: path("M2 20V4h20v16zm14.225-5.187Q18 13.625 18 12t-1.775-2.812T12 8T7.775 9.188T6 12t1.775 2.813T12 16t4.225-1.187");
}

</style>
