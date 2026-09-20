<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm1kgrbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-snippet-outline" /></template>
<style>
.pm1kgrbpr {
  fill: currentColor;
  d: path("M5 19h14V9.825L14.175 5H5zm0 2q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h10l6 6v10q0 .825-.587 1.413T19 21zm2-4h10v-2H7zm0-4h10v-2H7zm0-4h7V7H7zM5 19V5z");
}

</style>
