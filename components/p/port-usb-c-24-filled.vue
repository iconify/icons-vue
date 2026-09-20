<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej8so_b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-c-24-filled" /></template>
<style>
.ej8so_b9v {
  fill: currentColor;
  d: path("M19 12a2.996 2.996 0 0 1-3 3H8a3 3 0 0 1 0-6h8a2.996 2.996 0 0 1 3 3");
}

</style>
