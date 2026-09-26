<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wt0h0qbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pivot-16-filled" /></template>
<style>
.wt0h0qbew {
  fill: currentColor;
  d: path("M13.225 7.082a.5.5 0 0 1 .629.064l2 2a.5.5 0 1 1-.707.708L14 8.707V11.5a2.5 2.5 0 0 1-2.5 2.5H8.707l1.147 1.146a.5.5 0 1 1-.708.707l-2-2a.5.5 0 0 1 0-.707l2-2a.5.5 0 1 1 .708.707L8.707 13H11.5a1.5 1.5 0 0 0 1.5-1.5V8.707l-1.146 1.147a.5.5 0 1 1-.707-.708l2-2zM11.5 2A2.5 2.5 0 0 1 14 4.5v1.586a1.5 1.5 0 0 0-1.446.25l-.114.103l-6 6A1.5 1.5 0 0 0 6.087 14H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zM4.75 7a.75.75 0 0 0-.75.75v3.5c0 .414.336.75.75.75h.5a.75.75 0 0 0 .75-.75v-3.5A.75.75 0 0 0 5.25 7zm0-3a.75.75 0 0 0-.75.75v.5c0 .414.336.75.75.75h.5A.75.75 0 0 0 6 5.25v-.5A.75.75 0 0 0 5.25 4zm3 0a.75.75 0 0 0-.75.75v.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75v-.5a.75.75 0 0 0-.75-.75z");
}

</style>
