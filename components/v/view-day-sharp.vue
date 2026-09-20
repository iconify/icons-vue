<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzcjnca3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-day-sharp" /></template>
<style>
.kzcjnca3y {
  fill: currentColor;
  d: path("M4 18.77v-1h16v1zM4 15V9h16v6zm0-8.77v-1h16v1z");
}

</style>
