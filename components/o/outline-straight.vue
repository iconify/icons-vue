<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nphati1pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-straight" /></template>
<style>
.nphati1pw {
  fill: currentColor;
  d: path("M11 6.83L9.41 8.41L8 7l4-4l4 4l-1.41 1.41L13 6.83V21h-2z");
}

</style>
