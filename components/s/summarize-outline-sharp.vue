<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcx4sbows"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:summarize-outline-sharp" /></template>
<style>
.vcx4sbows {
  fill: currentColor;
  d: path("M7.192 8.808h1.616V7.192H7.192zm0 4h1.616v-1.616H7.192zm0 4h1.616v-1.616H7.192zM4 20V4h11.577L20 8.423V20zm1-1h14V9h-4V5H5zM5 5v4zv14z");
}

</style>
