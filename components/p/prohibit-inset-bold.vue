<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jh9s4q-vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:prohibit-inset-bold" /></template>
<style>
.jh9s4q-vl {
  fill: currentColor;
  d: path("M168.49 151.51a12 12 0 0 1-17 17l-64-64a12 12 0 0 1 17-17ZM236 128A108 108 0 1 1 128 20a108.12 108.12 0 0 1 108 108m-24 0a84 84 0 1 0-84 84a84.09 84.09 0 0 0 84-84");
}

</style>
