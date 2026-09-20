<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jsk901orb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-16-filled" /></template>
<style>
.jsk901orb {
  fill: currentColor;
  d: path("M6.235 2.192A1.5 1.5 0 0 0 4 3.499v9a1.5 1.5 0 0 0 2.235 1.308l8-4.5a1.5 1.5 0 0 0 0-2.615z");
}

</style>
