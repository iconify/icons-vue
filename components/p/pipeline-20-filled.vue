<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b7u2nhbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pipeline-20-filled" /></template>
<style>
.b7u2nhbkc {
  fill: currentColor;
  d: path("M2 5.5a1.5 1.5 0 0 1 3 0v9a1.5 1.5 0 0 1-3-.001zm13 0v9a1.5 1.5 0 0 0 3 0v-9a1.5 1.5 0 0 0-3 0M14 14V6H6v8z");
}

</style>
