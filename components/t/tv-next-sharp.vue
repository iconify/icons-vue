<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq7-6gbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-next-sharp" /></template>
<style>
.xq7-6gbbh {
  fill: currentColor;
  d: path("m19.5 21.73l-.73-.73l3-3l-3-3l.73-.73L23.23 18zM9 20v-2H3V4h18v8h-4v6h-2.23v2z");
}

</style>
