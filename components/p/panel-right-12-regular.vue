<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="el_va8b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-12-regular" /></template>
<style>
.el_va8b8t {
  fill: currentColor;
  d: path("M9 2H3a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2M2 8V4a1 1 0 0 1 1-1h4v6H3a1 1 0 0 1-1-1m8 0a1 1 0 0 1-1 1H8V3h1a1 1 0 0 1 1 1z");
}

</style>
