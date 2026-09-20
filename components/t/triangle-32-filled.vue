<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s2eae3bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-32-filled" /></template>
<style>
.s2eae3bar {
  fill: currentColor;
  d: path("M18.847 4.684c-1.235-2.242-4.457-2.243-5.693-.001L2.404 24.18C1.21 26.346 2.777 29 5.251 29h21.492c2.473 0 4.04-2.653 2.846-4.819z");
}

</style>
