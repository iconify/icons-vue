<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxsn4pb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:present-to-all-sharp" /></template>
<style>
.jxsn4pb8w {
  fill: currentColor;
  d: path("M11 16h2v-4.15l1.6 1.575L16.025 12L12 8l-4 4l1.425 1.4L11 11.825zm-9 4V4h20v16z");
}

</style>
