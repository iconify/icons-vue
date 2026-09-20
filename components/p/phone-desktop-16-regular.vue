<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a0cammb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-desktop-16-regular" /></template>
<style>
.a0cammb9j {
  fill: currentColor;
  d: path("M6 2h7a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H8v1h2v1H8v1h3.5a.5.5 0 0 0 0-1H11v-1h2a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v2h1V3a1 1 0 0 1 1-1M3.5 12a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm-1-6A1.5 1.5 0 0 0 1 7.5v6A1.5 1.5 0 0 0 2.5 15h3A1.5 1.5 0 0 0 7 13.5v-6A1.5 1.5 0 0 0 5.5 6zm0 1h3a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 .5-.5");
}

</style>
