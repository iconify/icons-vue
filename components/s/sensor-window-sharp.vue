<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1k14rbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sensor-window-sharp" /></template>
<style>
.m1k14rbeg {
  fill: currentColor;
  d: path("M4 22V2h16v20zm3-11h3v-1h4v1h3V5H7zm0 2v6h10v-6zM6 4v16h12V4z");
}

</style>
