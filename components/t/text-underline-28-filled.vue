<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="z-y35lbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-underline-28-filled" /></template>
<style>
.z-y35lbrx {
  fill: currentColor;
  d: path("M20 22a1 1 0 1 1 0 2H8a1 1 0 1 1 0-2zM19 4a1 1 0 0 1 1 1v9a6 6 0 0 1-12 0V5a1 1 0 0 1 2 0v9a4 4 0 0 0 8 0V5a1 1 0 0 1 1-1");
}

</style>
