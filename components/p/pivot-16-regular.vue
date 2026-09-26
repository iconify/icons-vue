<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fhtuowbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pivot-16-regular" /></template>
<style>
.fhtuowbln {
  fill: currentColor;
  d: path("M13.225 7.082a.5.5 0 0 1 .629.064l2 2a.5.5 0 1 1-.707.708L14 8.707V11.5a2.5 2.5 0 0 1-2.5 2.5H8.707l1.147 1.146a.5.5 0 1 1-.708.707l-2-2a.5.5 0 0 1 0-.707l2-2a.5.5 0 1 1 .708.707L8.707 13H11.5a1.5 1.5 0 0 0 1.5-1.5V8.707l-1.146 1.147a.5.5 0 1 1-.707-.708l2-2zM11.5 2A2.5 2.5 0 0 1 14 4.5v1.586a1.5 1.5 0 0 0-1 0V4.5A1.5 1.5 0 0 0 11.5 3h-7A1.5 1.5 0 0 0 3 4.5v7A1.5 1.5 0 0 0 4.5 13h1.588a1.5 1.5 0 0 0 0 1H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zM5.25 7a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-.75.75h-.5a.75.75 0 0 1-.75-.75v-3.5A.75.75 0 0 1 4.75 7zm0-3a.75.75 0 0 1 .75.75v.5a.75.75 0 0 1-.75.75h-.5A.75.75 0 0 1 4 5.25v-.5A.75.75 0 0 1 4.75 4zm6 0a.75.75 0 0 1 .75.75v.5a.75.75 0 0 1-.75.75h-3.5A.75.75 0 0 1 7 5.25v-.5A.75.75 0 0 1 7.75 4z");
}

</style>
