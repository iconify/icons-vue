<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z58tk59sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-chart-sharp" /></template>
<style>
.z58tk59sw {
  fill: currentColor;
  d: path("M3 8V3h18v5zm0 13V10h4.5v11zm13.5 0V10H21v11zm-7 0V10h5v11z");
}

</style>
