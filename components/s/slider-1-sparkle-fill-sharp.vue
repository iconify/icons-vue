<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnnshcblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-sparkle-fill-sharp" /></template>
<style>
.tnnshcblg {
  fill: currentColor;
  d: path("M14.989 4.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L17 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L19 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 7a1 1 0 0 1 0-2ZM4.171 7H3a1 1 0 0 1 0-2h1.171a3 3 0 0 1 5.658 0H11a1 1 0 0 1 0 2H9.829a3 3 0 0 1-5.658 0m6 12H3a1 1 0 0 1 0-2h7.171a3 3 0 0 1 5.658 0H21a1 1 0 0 1 0 2h-5.171a3 3 0 0 1-5.658 0");
}

</style>
