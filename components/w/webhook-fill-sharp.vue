<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0yja1l6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webhook-fill-sharp" /></template>
<style>
.n0yja1l6u {
  fill: currentColor;
  d: path("M9 7v10a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0a1 1 0 0 1-2 0a3 3 0 1 0-6 0m7 7h-4a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0v5h3a5 5 0 0 1 0 10a1 1 0 0 1 0-2a3 3 0 1 0 0-6m-4 2h4a1 1 0 0 1 0 2h-3.099A5.002 5.002 0 0 1 3 17a1 1 0 0 1 2 0a3 3 0 1 0 6 0a1 1 0 0 1 1-1");
}

</style>
