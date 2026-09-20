<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h8t-23-iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:megaphone-20-filled" /></template>
<style>
.h8t-23-iu {
  fill: currentColor;
  d: path("M16.113 3.352A1.5 1.5 0 0 1 18 4.802v10.31a1.5 1.5 0 0 1-1.974 1.424L11.27 14.95A3.25 3.25 0 0 1 5 13.75v-.89l-1.974-.658A1.5 1.5 0 0 1 2 10.78V8.27a1.5 1.5 0 0 1 1.114-1.45zM6 13.194v.556a2.25 2.25 0 0 0 4.32.884z");
}

</style>
