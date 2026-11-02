<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5gmqgb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-fill" /></template>
<style>
.h5gmqgb7z {
  fill: currentColor;
  d: path("M11 3c1.039 0 1.992.578 2.707 1.293l6 6a2.414 2.414 0 0 1 0 3.414l-6 6a2.414 2.414 0 0 1-3.414 0l-6-6C3.578 12.992 3 12.039 3 11V6a3 3 0 0 1 3-3ZM7.158 8.221a2 2 0 1 0 3.684 1.558A2 2 0 0 0 7.158 8.22");
}

</style>
