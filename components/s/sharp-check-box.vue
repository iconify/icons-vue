<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-9__5ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-check-box" /></template>
<style>
.g6-9__5ga {
  fill: currentColor;
  d: path("M21 3H3v18h18zM10 17l-5-5l1.41-1.41L10 14.17l7.59-7.59L19 8z");
}

</style>
