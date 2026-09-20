<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="likd4yb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-grid-20-regular" /></template>
<style>
.likd4yb1u {
  fill: currentColor;
  d: path("M5 6a1 1 0 0 0-1 1v1.5a1 1 0 0 0 1 1h3.5a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1zm3.5 1v1.5H5V7zM4 11.5a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1V13a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1zm1 0V13h3.5v-1.5zM11.5 6H15a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1h-3.5a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1M15 7h-3.5v1.5H15zm-4.5 4.5a1 1 0 0 1 1-1H15a1 1 0 0 1 1 1V13a1 1 0 0 1-1 1h-3.5a1 1 0 0 1-1-1zm1 0V13H15v-1.5zM2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1z");
}

</style>
