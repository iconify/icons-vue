<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7573mrea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-8-bulk" /></template>
<style>
.w7573mrea {
  fill: currentColor;
  d: path("M12 12a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-3.145-1.112A5.002 5.002 0 0 1 12 2a5.001 5.001 0 0 1 3.145 8.888A6.001 6.001 0 0 1 12 22a6 6 0 0 1-3.145-11.112M12 4a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

</style>
