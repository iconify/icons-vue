<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="latijlb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-left-28-regular" /></template>
<style>
.latijlb7z {
  fill: currentColor;
  d: path("M3 24.25a.75.75 0 0 0 1.5 0V3.75a.75.75 0 0 0-1.5 0zm22-17.5A3.75 3.75 0 0 0 21.25 3H10.5a1 1 0 0 0-1 1v20a1 1 0 0 0 1 1h10.75A3.75 3.75 0 0 0 25 21.25zM11 18.5h6v5h-6zm6-1.5h-6v-6h6zm1.5 1.5h5v2.75a2.25 2.25 0 0 1-2.25 2.25H18.5zm5-1.5h-5v-6h5zm0-10.25V9.5h-5v-5h2.75a2.25 2.25 0 0 1 2.25 2.25M17 4.5v5h-6v-5z");
}

</style>
