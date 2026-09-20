<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j4u34nyhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-16-regular" /></template>
<style>
.j4u34nyhv {
  fill: currentColor;
  d: path("M8 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0 4a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-1 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
