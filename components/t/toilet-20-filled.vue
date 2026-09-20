<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wym-vnbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toilet-20-filled" /></template>
<style>
.wym-vnbxz {
  fill: currentColor;
  d: path("M15.997 16a2 2 0 0 1-2 2h-8a1 1 0 0 1-.908-1.419l.863-1.872a6.995 6.995 0 0 0 10.045-2.099zm-2.823-6a3 3 0 0 0 2.076 1.901A5.99 5.99 0 0 1 10.001 15a6 6 0 0 1-5.915-5zM16.5 1A1.5 1.5 0 0 1 18 2.5V9a2 2 0 1 1-4 0V2.5A1.5 1.5 0 0 1 15.5 1zM13 9H4.5a1.5 1.5 0 1 1 0-3H13z");
}

</style>
