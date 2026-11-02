<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgb3ob_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warning-bulk" /></template>
<style>
.hlgb3ob_q {
  fill: currentColor;
  d: path("M13 14a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0Zm-.99 3a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
