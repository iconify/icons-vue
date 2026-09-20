<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r15zbbb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:margin-sharp" /></template>
<style>
.r15zbbb0j {
  fill: currentColor;
  d: path("M4 20V4h16v16zM7.346 8.904h1.538V7.365H7.346zm3.885 0h1.538V7.365h-1.538zm3.885 0h1.538V7.365h-1.538zm-7.77 3.865h1.539v-1.538H7.346zm3.885 0h1.538v-1.538h-1.538zm3.885 0h1.538v-1.538h-1.538z");
}

</style>
