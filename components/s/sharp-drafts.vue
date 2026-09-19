<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5_gnccui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-drafts" /></template>
<style>
.q5_gnccui {
  fill: currentColor;
  d: path("M21.99 6.86L12 1L2 6.86V20h20zM12 13L3.74 7.84L12 3l8.26 4.84z");
}

</style>
