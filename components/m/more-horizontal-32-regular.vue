<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ldspctbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-horizontal-32-regular" /></template>
<style>
.ldspctbcu {
  fill: currentColor;
  d: path("M9.5 16a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m9 0a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m6.5 2.5a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

</style>
