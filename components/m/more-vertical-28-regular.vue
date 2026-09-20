<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e64xl3r0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-28-regular" /></template>
<style>
.e64xl3r0r {
  fill: currentColor;
  d: path("M14 8.25a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5m0 8a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5M11.75 22a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 0 0-4.5 0");
}

</style>
