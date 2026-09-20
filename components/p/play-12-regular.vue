<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q3f5mea1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-12-regular" /></template>
<style>
.q3f5mea1s {
  fill: currentColor;
  d: path("M3 2.862a1 1 0 0 1 1.496-.868l5.492 3.138a1 1 0 0 1 0 1.736l-5.492 3.139A1 1 0 0 1 3 9.139zM9.492 6L4 2.862v6.277z");
}

</style>
