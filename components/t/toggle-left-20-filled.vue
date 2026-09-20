<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o7ik_yyie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-20-filled" /></template>
<style>
.o7ik_yyie {
  fill: currentColor;
  d: path("M14 6a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8zm-8 6a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
