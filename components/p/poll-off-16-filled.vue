<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="syj-8ek5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-off-16-filled" /></template>
<style>
.syj-8ek5h {
  fill: currentColor;
  d: path("M6 6.707V13a2 2 0 1 0 4 0v-2.293l1 1V13a2 2 0 0 0 3.016 1.723l.13.13a.5.5 0 0 0 .708-.707l-13-13a.5.5 0 1 0-.708.708zM11 7v1.879l4 4V7a2 2 0 1 0-4 0M6 3v.879l4 4V3a2 2 0 1 0-4 0M1 9a2 2 0 1 1 4 0v4a2 2 0 1 1-4 0z");
}

</style>
