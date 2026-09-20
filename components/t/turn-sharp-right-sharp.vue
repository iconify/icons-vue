<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg4llmb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-sharp-right-sharp" /></template>
<style>
.qg4llmb_d {
  fill: currentColor;
  d: path("M6 21v-8h10V6.8l-1.6 1.6L13 7l4-4l4 4l-1.4 1.4L18 6.8V15H8v6z");
}

</style>
