<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5wztebku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-32-filled" /></template>
<style>
.j5wztebku {
  fill: currentColor;
  d: path("M17 7V2H7a1 1 0 0 0-1 1v11h20V3a1 1 0 0 0-1-1h-2v7a1 1 0 1 1-2 0V2h-2v5a1 1 0 1 1-2 0m9 9H6v2.75A3.25 3.25 0 0 0 9.25 22H13v5a3 3 0 1 0 6 0v-5h3.75A3.25 3.25 0 0 0 26 18.75z");
}

</style>
