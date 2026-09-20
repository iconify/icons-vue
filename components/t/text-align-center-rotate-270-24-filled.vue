<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4s5b6bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-center-rotate-270-24-filled" /></template>
<style>
.q4s5b6bua {
  fill: currentColor;
  d: path("M6 20a1 1 0 0 1-1-1V5a1 1 0 0 1 2 0v14a1 1 0 0 1-1 1m12-2a1 1 0 0 1-1-1V7a1 1 0 1 1 2 0v10a1 1 0 0 1-1 1m-7 3a1 1 0 1 0 2 0V3a1 1 0 1 0-2 0z");
}

</style>
