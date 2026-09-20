<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sif429gbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:package-2-outline-sharp" /></template>
<style>
.sif429gbk {
  fill: currentColor;
  d: path("M11 19.425v-6.85L5 9.1v6.85zm2 0l6-3.475V9.1l-6 3.475zM12 22.3l-9-5.175V6.875L12 1.7l9 5.175v10.25zm4-13.775l1.925-1.1L12 4l-1.95 1.125zm-4 2.325l1.95-1.125L8.025 6.3l-1.95 1.125z");
}

</style>
