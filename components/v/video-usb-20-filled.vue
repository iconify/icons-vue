<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fd3_lt7uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-usb-20-filled" /></template>
<style>
.fd3_lt7uk {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h5a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H7.168l.45-.618A2 2 0 0 0 8 13.206V11a2 2 0 0 0-1-1.732V8a2 2 0 0 0-2-2zm14.037 7.776L15 12.369V5.63l2.037-1.406a1.25 1.25 0 0 1 1.96 1.028v7.495a1.25 1.25 0 0 1-1.96 1.029M2 8v2a1 1 0 0 0-1 1v2.179a1 1 0 0 0 .187.582L2.5 15.594V17a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-1.406l1.309-1.8A1 1 0 0 0 7 13.206V11a1 1 0 0 0-1-1V8a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1m3 2H3V8h2z");
}

</style>
