<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqvuwrxxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-terminal-fill" /></template>
<style>
.mqvuwrxxf {
  fill: currentColor;
  d: path("M22 6v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3M4 18a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V9H4Zm3.707-6.707l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L7.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414M13 15h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
