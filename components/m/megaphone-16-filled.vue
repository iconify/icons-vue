<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o7r192-sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:megaphone-16-filled" /></template>
<style>
.o7r192-sd {
  fill: currentColor;
  d: path("M15 3.503a1.5 1.5 0 0 0-1.98-1.421l-11 3.715A1.5 1.5 0 0 0 1 7.217v1.566a1.5 1.5 0 0 0 1.018 1.42L4 10.877V12a3 3 0 0 0 5.872.868l3.146 1.067A1.5 1.5 0 0 0 15 12.515zM5 11.215l3.924 1.332A2 2 0 0 1 5 12z");
}

</style>
