<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tto0fbi1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-local-bar" /></template>
<style>
.tto0fbi1o {
  fill: currentColor;
  d: path("M21 4.45c0-.8-.65-1.45-1.45-1.45H4.45C3.65 3 3 3.65 3 4.45c0 .35.13.7.37.96L11 14v5H7c-.55 0-1 .45-1 1s.45 1 1 1h10c.55 0 1-.45 1-1s-.45-1-1-1h-4v-5l7.63-8.59c.24-.26.37-.61.37-.96M7.43 7L5.66 5h12.69l-1.78 2z");
}

</style>
