<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ozq-vnblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-android-32-regular" /></template>
<style>
.ozq-vnblc {
  fill: currentColor;
  d: path("M22 7.5a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0M24.5 3a4.5 4.5 0 0 0-4.372 5.568l-9.15 4.575a4.5 4.5 0 1 0 0 5.713l9.15 4.576Q20 23.946 20 24.5a4.5 4.5 0 1 0 1.023-2.857l-9.15-4.575a4.5 4.5 0 0 0 0-2.136l9.15-4.575A4.5 4.5 0 1 0 24.5 3M5 16a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0m19.5 6a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
