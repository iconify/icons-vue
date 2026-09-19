<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnglvbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-currency-lira" /></template>
<style>
.mwnglvbvt {
  fill: currentColor;
  d: path("M9 8.76V3h2v4.51L15 5v2.36l-4 2.51l.01 2.35L15 9.72v2.36l-4 2.51V19c2.76 0 5-2.24 5-5h2c0 3.87-3.13 7-7 7H9v-5.16l-3 1.88v-2.36l3-1.88v-2.36L6 13v-2.36z");
}

</style>
