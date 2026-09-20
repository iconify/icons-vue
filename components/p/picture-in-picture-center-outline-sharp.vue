<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e826usbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-center-outline-sharp" /></template>
<style>
.e826usbko {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm0 0V6zm4-3h8V9H8z");
}

</style>
