<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_n420b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-frame-2-sharp" /></template>
<style>
.m_n420b3v {
  fill: currentColor;
  d: path("M20 10V7h-3V6h4v4zM3 10V6h4v1H4v3zm14 8v-1h3v-3h1v4zM3 18v-4h1v3h3v1z");
}

</style>
