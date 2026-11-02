<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g88fmc7vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-lock-fill-sharp" /></template>
<style>
.g88fmc7vd {
  fill: currentColor;
  d: path("M20 2a1 1 0 0 1 1 1v7c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V3a1 1 0 0 1 1-1Zm-5 7a3 3 0 1 0-6 0a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1m-2 0h-2a1 1 0 0 1 2 0");
}

</style>
