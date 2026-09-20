<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u5i80ht_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-color-accent-16-filled" /></template>
<style>
.u5i80ht_a {
  fill: currentColor;
  d: path("M2.5 11.167c0-.368.246-.667.55-.667h9.9c.304 0 .55.299.55.667v2.666c0 .368-.246.667-.55.667h-9.9c-.304 0-.55-.299-.55-.667z");
}

</style>
