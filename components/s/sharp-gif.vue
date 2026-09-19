<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s083s7bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-gif" /></template>
<style>
.s083s7bdr {
  fill: currentColor;
  d: path("M11.5 9H13v6h-1.5zM10 9H5v6h5v-3H8.5v1.5h-2v-3H10zm9 1.5V9h-4.5v6H16v-2h2v-1.5h-2v-1z");
}

</style>
