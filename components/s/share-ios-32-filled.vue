<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="daplktanq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-ios-32-filled" /></template>
<style>
.daplktanq {
  fill: currentColor;
  d: path("M16.884 2.366a1.25 1.25 0 0 0-1.768 0l-7.75 7.75a1.25 1.25 0 0 0 1.768 1.768l5.616-5.616V20.75a1.25 1.25 0 1 0 2.5 0V6.268l5.616 5.616a1.25 1.25 0 0 0 1.768-1.768zM5.5 16.25a1.25 1.25 0 1 0-2.5 0v8.25A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5v-8.25a1.25 1.25 0 1 0-2.5 0v8.25a2 2 0 0 1-2 2h-17a2 2 0 0 1-2-2z");
}

</style>
