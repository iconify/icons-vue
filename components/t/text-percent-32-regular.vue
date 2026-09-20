<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nb196ovss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-percent-32-regular" /></template>
<style>
.nb196ovss {
  fill: currentColor;
  d: path("M24.653 3.171a1 1 0 0 1 .27 1.388l-16.188 24a1 1 0 1 1-1.658-1.118l16.188-24a1 1 0 0 1 1.388-.27M9 5a4 4 0 1 0 0 8a4 4 0 0 0 0-8M3 9a6 6 0 1 1 12 0A6 6 0 0 1 3 9m16 14a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-6a6 6 0 1 0 0 12a6 6 0 0 0 0-12");
}

</style>
