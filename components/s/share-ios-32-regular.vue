<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="haxhunbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-ios-32-regular" /></template>
<style>
.haxhunbvk {
  fill: currentColor;
  d: path("M16.707 2.293a1 1 0 0 0-1.414 0l-8 8a1 1 0 1 0 1.414 1.414L15 5.414V21a1 1 0 1 0 2 0V5.414l6.293 6.293a1 1 0 0 0 1.414-1.414zM5 16a1 1 0 1 0-2 0v8.5A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5V16a1 1 0 1 0-2 0v8.5a2.5 2.5 0 0 1-2.5 2.5h-17A2.5 2.5 0 0 1 5 24.5z");
}

</style>
