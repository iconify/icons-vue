<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uudn08bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-add-a-photo" /></template>
<style>
.uudn08bwh {
  fill: currentColor;
  d: path("M21 6h-3.17L16 4h-6v2h5.12l1.83 2H21v12H5v-9H3v9c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2M8 14c0 2.76 2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5s-5 2.24-5 5m5-3c1.65 0 3 1.35 3 3s-1.35 3-3 3s-3-1.35-3-3s1.35-3 3-3M5 6h3V4H5V1H3v3H0v2h3v3h2z");
}

</style>
