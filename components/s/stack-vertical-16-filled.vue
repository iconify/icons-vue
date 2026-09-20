<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m2qmjpdpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-vertical-16-filled" /></template>
<style>
.m2qmjpdpt {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v8.75a.75.75 0 0 1-1.5 0V11.5a1 1 0 0 0-1-1h-7a1 1 0 0 0-1 1v1.75a.75.75 0 0 1-1.5 0V4.5A2.5 2.5 0 0 1 4.5 2zm-7 5a1 1 0 0 0-1 1v1.209A2.5 2.5 0 0 1 4.5 9h7c.356 0 .694.075 1 .209V8a1 1 0 0 0-1-1zm0-3.5a1 1 0 0 0-1 1v1.209a2.5 2.5 0 0 1 1-.209h7c.356 0 .694.075 1 .209V4.5a1 1 0 0 0-1-1z");
}

</style>
