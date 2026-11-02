<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsag_6coy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-fill" /></template>
<style>
.hsag_6coy {
  fill: currentColor;
  d: path("M17 5h3a1 1 0 0 1 0 2h-1v12a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V7H4a1 1 0 0 1 0-2h3a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3m-3-1h-4a.997.997 0 0 0-1 1h6a.997.997 0 0 0-1-1m-5 6v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0m4 0v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0");
}

</style>
