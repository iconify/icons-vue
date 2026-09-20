<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g31eslbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-16-regular" /></template>
<style>
.g31eslbwy {
  fill: currentColor;
  d: path("M11.02 11.727a5.5 5.5 0 1 1 .707-.707l3.127 3.126a.5.5 0 0 1-.708.708zM12 7.5a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0");
}

</style>
