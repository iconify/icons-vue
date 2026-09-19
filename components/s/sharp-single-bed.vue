<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snz1_usas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-single-bed" /></template>
<style>
.snz1_usas {
  fill: currentColor;
  d: path("M18 10V5H6v5H4v7h1.33L6 19h1l.67-2h8.67l.66 2h1l.67-2H20v-7zm-7 0H8V7h3zm5 0h-3V7h3z");
}

</style>
