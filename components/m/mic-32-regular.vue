<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6kqm8j3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-32-regular" /></template>
<style>
.i6kqm8j3v {
  fill: currentColor;
  d: path("M16 2a6 6 0 0 0-6 6v8a6 6 0 0 0 12 0V8a6 6 0 0 0-6-6m4 14a4 4 0 0 1-8 0V8a4 4 0 0 1 8 0zM7 15a1 1 0 0 1 1 1a8 8 0 1 0 16 0a1 1 0 1 1 2 0c0 5.186-3.947 9.45-9.001 9.95L17 26v3a1 1 0 1 1-2 0v-3l.001-.05C9.947 25.45 6 21.187 6 16a1 1 0 0 1 1-1");
}

</style>
