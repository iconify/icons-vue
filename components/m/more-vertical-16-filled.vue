<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xi3uo3lof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-16-filled" /></template>
<style>
.xi3uo3lof {
  fill: currentColor;
  d: path("M8 5.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m0 4a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5M6.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 0 0-2.5 0");
}

</style>
