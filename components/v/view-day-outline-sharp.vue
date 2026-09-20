<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9vlk6zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-day-outline-sharp" /></template>
<style>
.bh9vlk6zh {
  fill: currentColor;
  d: path("M4 18.77v-1h16v1zM4 15V9h16v6zm1-1h14v-4H5zM4 6.23v-1h16v1zM5 14v-4z");
}

</style>
