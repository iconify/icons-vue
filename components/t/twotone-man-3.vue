<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtifbgitp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-man-3" /></template>
<style>
.mtifbgitp {
  fill: currentColor;
  d: path("M14 7h-4c-1.1 0-2 .9-2 2v6h2v7h4v-7h2V9c0-1.1-.9-2-2-2m-2-5.249L14.248 4L12 6.248L9.75 4z");
}

</style>
