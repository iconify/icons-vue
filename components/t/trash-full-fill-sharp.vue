<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqrh3kgzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-fill-sharp" /></template>
<style>
.dqrh3kgzf {
  fill: currentColor;
  d: path("M16 2a1 1 0 0 1 1 1v2h3a1 1 0 0 1 0 2h-1v14a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7H4a1 1 0 0 1 0-2h3V3a1 1 0 0 1 1-1Zm-1 2H9v1h6Zm-6 6v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0m4 0v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0");
}

</style>
