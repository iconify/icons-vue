<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h0j9m0b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tv-usb-20-filled" /></template>
<style>
.h0j9m0b3l {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v1.268A2 2 0 0 0 17 7h-2a2 2 0 0 0-2 2v1.268A2 2 0 0 0 12 12v2.179a2 2 0 0 0 .176.821H4a2 2 0 0 1-2-2zm15 2a1 1 0 0 1 1 1v2a1 1 0 0 1 1 1v2.206a1 1 0 0 1-.191.588l-1.309 1.8V18a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1v-1.406l-1.313-1.833A1 1 0 0 1 13 14.18V12a1 1 0 0 1 1-1V9a1 1 0 0 1 1-1zm0 3V9h-2v2zm-3.5 5.915L12.845 16H5.5a.5.5 0 0 0 0 1h8zm-.313-2.154l-.333.239Z");
}

</style>
