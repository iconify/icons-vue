<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txcp15bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-network-cell" /></template>
<style>
.txcp15bpc {
  fill: currentColor;
  d: path("M4.41 22H21c.55 0 1-.45 1-1V4.41c0-.89-1.08-1.34-1.71-.71L3.71 20.29c-.63.63-.19 1.71.7 1.71M20 20h-3V9.83l3-3z");
}

</style>
