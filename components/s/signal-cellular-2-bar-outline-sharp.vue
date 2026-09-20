<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi9wkcbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-2-bar-outline-sharp" /></template>
<style>
.yi9wkcbtj {
  fill: currentColor;
  d: path("M3 21L21 3v18zm9.289-1H20V5.427l-7.711 7.712z");
}

</style>
