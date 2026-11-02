<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6oh2umiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-left-fill-sharp" /></template>
<style>
.m6oh2umiq {
  fill: currentColor;
  d: path("M20 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-6 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm6 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-6 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

</style>
