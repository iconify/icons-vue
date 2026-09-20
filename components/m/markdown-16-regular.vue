<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vuy9k2bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:markdown-16-regular" /></template>
<style>
.vuy9k2bmt {
  fill: currentColor;
  d: path("M9.124 3.17A.5.5 0 0 1 10 3.5v8a.5.5 0 0 1-1 0V4.83l-2.624 3a.5.5 0 0 1-.752 0L3 4.83v6.67a.5.5 0 0 1-1 0v-8a.5.5 0 0 1 .876-.33L6 6.742zM13.5 3a.5.5 0 0 1 .5.5v6.793l1.146-1.147a.5.5 0 1 1 .707.708l-2 2a.5.5 0 0 1-.707 0l-2-2a.5.5 0 1 1 .707-.708L13 10.293V3.5a.5.5 0 0 1 .5-.5");
}

</style>
