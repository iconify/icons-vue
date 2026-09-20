<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="crr4zjb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-28-regular" /></template>
<style>
.crr4zjb9t {
  fill: currentColor;
  d: path("M4.5 3.75a.75.75 0 0 0-1.5 0v20.5a.75.75 0 0 0 1.5 0zM25 5.254c0-1.816-2.041-2.884-3.533-1.848l-12.504 8.68a2.25 2.25 0 0 0-.013 3.688l12.504 8.81c1.49 1.05 3.546-.015 3.546-1.839zm-2.678-.616a.75.75 0 0 1 1.178.616v17.491a.75.75 0 0 1-1.182.613l-12.504-8.81a.75.75 0 0 1 .004-1.23z");
}

</style>
