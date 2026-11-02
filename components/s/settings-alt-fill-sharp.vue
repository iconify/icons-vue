<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sce0wgj8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt-fill-sharp" /></template>
<style>
.sce0wgj8r {
  fill: currentColor;
  d: path("M21 7v10a1 1 0 0 1-.553.894l-8 4a1 1 0 0 1-.894 0l-8-4A1 1 0 0 1 3 17V7c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0l8 4A1 1 0 0 1 21 7M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
