<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dyezhy-oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-32-regular" /></template>
<style>
.dyezhy-oa {
  fill: currentColor;
  d: path("M29 25a1 1 0 1 1 0 2H8a1 1 0 1 1 0-2zM8.75 9a6.75 6.75 0 1 1 0 13.5a6.75 6.75 0 0 1 0-13.5m-3 6a.75.75 0 0 0 0 1.5h6a.75.75 0 0 0 0-1.5zM29 18a1 1 0 1 1 0 2H19a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H19a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H8a1 1 0 0 1 0-2z");
}

</style>
