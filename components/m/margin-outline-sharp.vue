<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz-ke3zem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:margin-outline-sharp" /></template>
<style>
.uz-ke3zem {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5zM7.346 8.904V7.365h1.538v1.539zm3.885 0V7.365h1.538v1.539zm3.885 0V7.365h1.538v1.539zm-7.77 3.865v-1.538h1.539v1.538zm3.885 0v-1.538h1.538v1.538zm3.885 0v-1.538h1.538v1.538z");
}

</style>
