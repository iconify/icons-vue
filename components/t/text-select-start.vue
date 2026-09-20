<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kibcwsb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-start" /></template>
<style>
.kibcwsb6p {
  fill: currentColor;
  d: path("M11 21v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zM3 21v-2h2V5H3V3h6v2H7v14h2v2z");
}

</style>
