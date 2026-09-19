<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is0ef8d7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-flash-off" /></template>
<style>
.is0ef8d7x {
  fill: currentColor;
  d: path("M17 10h-3.61l2.28 2.28zm0-8H7v1.61l6.13 6.13zm-13.59.86L2 4.27l5 5V13h3v9l3.58-6.15L17.73 20l1.41-1.41z");
}

</style>
