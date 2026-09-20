<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="joeaqm0lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-line-spacing-32-filled" /></template>
<style>
.joeaqm0lx {
  fill: currentColor;
  d: path("M25.25 18c.69 0 1.25.56 1.25 1.25v5.482l.866-.866a1.25 1.25 0 0 1 1.768 1.768l-3 3a1.25 1.25 0 0 1-1.673.086l-.095-.086l-3-3a1.25 1.25 0 0 1 1.768-1.768l.866.866V19.25c0-.69.56-1.25 1.25-1.25m-11.5 6a1.25 1.25 0 1 1 0 2.5h-9.5a1.25 1.25 0 1 1 0-2.5zm5-9a1.25 1.25 0 1 1 0 2.5H4.25a1.25 1.25 0 1 1 0-2.5zm5.71-11.72a1.25 1.25 0 0 1 1.674.086l3 3a1.25 1.25 0 1 1-1.768 1.768l-.866-.866v5.482a1.25 1.25 0 1 1-2.5 0V7.268l-.866.866a1.25 1.25 0 1 1-1.768-1.768l3-3zM13.75 6a1.25 1.25 0 1 1 0 2.5h-9.5a1.25 1.25 0 1 1 0-2.5z");
}

</style>
