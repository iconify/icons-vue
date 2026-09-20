<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="neu8iqbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:warehouse-thin" /></template>
<style>
.neu8iqbas {
  fill: currentColor;
  d: path("M240 188h-12V54.66l12.84-2.75a4 4 0 1 0-1.68-7.82l-224 48A4 4 0 0 0 16 100a4 4 0 0 0 .84-.09L28 97.52V188H16a4 4 0 0 0 0 8h224a4 4 0 0 0 0-8M36 95.81l184-39.43V188h-32v-60a4 4 0 0 0-4-4H72a4 4 0 0 0-4 4v60H36ZM180 156H76v-24h104Zm-104 8h104v24H76Z");
}

</style>
