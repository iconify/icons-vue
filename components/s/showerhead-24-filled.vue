<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc4cr9bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:showerhead-24-filled" /></template>
<style>
.tc4cr9bve {
  fill: currentColor;
  d: path("m21.49 4.982l-2.01 2.01a9 9 0 0 0-2.47-2.47l2.01-2.01a1.747 1.747 0 1 1 2.47 2.47M5.28 13.72a.75.75 0 0 1 0 1.06l-2 2a.75.75 0 0 1-1.06-1.06l2-2a.75.75 0 0 1 1.06 0m2.5 3.56a.75.75 0 1 0-1.06-1.06l-2 2a.75.75 0 1 0 1.06 1.06zm2.5 2.5a.75.75 0 1 0-1.06-1.06l-2 2a.75.75 0 1 0 1.06 1.06zM3.736 7.263a1.75 1.75 0 0 1 2.473 0l10.56 10.559a1.749 1.749 0 1 1-2.474 2.473L3.736 9.736a1.75 1.75 0 0 1 0-2.473m3.18-.707a3 3 0 0 0-.43-.352a8 8 0 0 1 11.316 11.304a3 3 0 0 0-.327-.393z");
}

</style>
