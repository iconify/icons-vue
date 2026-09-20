<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td9wy-b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:voice-chat-sharp" /></template>
<style>
.td9wy-b2z {
  fill: currentColor;
  d: path("M6 11h1.5V9H6zm2.5 2H10V7H8.5zm2.75 2h1.5V5h-1.5zM14 13h1.5V7H14zm2.5-2H18V9h-1.5zM2 22V2h20v16H6z");
}

</style>
