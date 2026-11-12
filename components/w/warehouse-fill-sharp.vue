<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3a8_261r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-fill-sharp" /></template>
<style>
.a3a8_261r {
  fill: currentColor;
  d: path("M21 22h-5v-9a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1v9H3a1 1 0 0 1 0-2h1V10c0-.379.214-.725.553-.894l6-3A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l6 3A1 1 0 0 1 20 10v10h1a1 1 0 0 1 0 2m-8-6h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m0 4h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
