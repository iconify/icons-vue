<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up0cnugah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:summarize-outline-sharp" /></template>
<style>
.up0cnugah {
  fill: currentColor;
  d: path("M7 9h2V7H7zm0 4h2v-2H7zm0 4h2v-2H7zm-4 4V3h13l5 5v13zm2-2h14V9h-4V5H5zM5 5v4zv14z");
}

</style>
