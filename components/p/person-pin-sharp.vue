<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5m-g8l8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:person-pin-sharp" /></template>
<style>
.m5m-g8l8e {
  fill: currentColor;
  d: path("m12 23l-3-3H3V2h18v18h-6zm2.475-12.025Q15.5 9.95 15.5 8.5t-1.025-2.475T12 5T9.525 6.025T8.5 8.5t1.025 2.475T12 12t2.475-1.025M5 18h14v-1.15q-1.35-1.325-3.137-2.087T12 14t-3.863.763T5 16.85z");
}

</style>
