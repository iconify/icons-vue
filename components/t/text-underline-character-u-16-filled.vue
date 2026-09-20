<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gq0r0u4ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-underline-character-u-16-filled" /></template>
<style>
.gq0r0u4ky {
  fill: currentColor;
  d: path("M6 2.75a.75.75 0 0 0-1.5 0V7.5a3.5 3.5 0 1 0 7 0V2.75a.75.75 0 0 0-1.5 0V7.5a2 2 0 1 1-4 0zM4.75 12.5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5z");
}

</style>
