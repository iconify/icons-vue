<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bi49ouboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-list-roman-numeral-uppercase-20-filled" /></template>
<style>
.bi49ouboa {
  fill: currentColor;
  d: path("M5 1.5a.5.5 0 0 0-1 0v4a.5.5 0 0 0 1 0zM8.75 4a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zm0 5a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zm0 5a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zM4.5 7a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 .5-.5m.5 6.5a.5.5 0 0 0-1 0v4a.5.5 0 0 0 1 0z");
}

</style>
