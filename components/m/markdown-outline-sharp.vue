<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-ji1bbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:markdown-outline-sharp" /></template>
<style>
.y-ji1bbzy {
  fill: currentColor;
  d: path("m16 15l3-3l-1.05-1.075l-1.2 1.2V9h-1.5v3.125l-1.2-1.2L13 12zM2 20V4h20v16zm2-2h16V6H4zm0 0V6zm1.5-3H7v-4.5h1v3h1.5v-3h1V15H12V9H5.5z");
}

</style>
