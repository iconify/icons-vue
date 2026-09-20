<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mweid1b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-16-regular" /></template>
<style>
.mweid1b7w {
  fill: currentColor;
  d: path("M2.5 9h11a.5.5 0 0 1 .09.992L13.5 10h-11a.5.5 0 0 1-.09-.992zh11zm0-3h11a.5.5 0 0 1 .09.992L13.5 7h-11a.5.5 0 0 1-.09-.992zh11z");
}

</style>
