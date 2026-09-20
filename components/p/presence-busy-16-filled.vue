<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iuqq3yhus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-busy-16-filled" /></template>
<style>
.iuqq3yhus {
  fill: currentColor;
  d: path("M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0");
}

</style>
