<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="l666nccly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-ios-28-regular" /></template>
<style>
.l666nccly {
  fill: currentColor;
  d: path("M14 2a.75.75 0 0 1 .53.22l6.75 6.75a.75.75 0 1 1-1.06 1.06l-5.47-5.47v13.69a.75.75 0 0 1-1.5 0V4.56l-5.47 5.47a.75.75 0 1 1-1.06-1.06l6.75-6.75A.75.75 0 0 1 14 2M4.5 13.75a.75.75 0 0 0-1.5 0v7.5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25v-7.5a.75.75 0 0 0-1.5 0v7.5a2.25 2.25 0 0 1-2.25 2.25H6.75a2.25 2.25 0 0 1-2.25-2.25z");
}

</style>
