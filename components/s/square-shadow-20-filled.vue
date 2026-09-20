<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kl150d5xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-shadow-20-filled" /></template>
<style>
.kl150d5xs {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14H6v1.5A2.5 2.5 0 0 0 8.5 18h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 15.5 6H14V4.5A2.5 2.5 0 0 0 11.5 2zm-1 2.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1z");
}

</style>
