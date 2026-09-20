<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q7vjvmbdo"/><path class="wut168b0z"/><path class="ffqcrz2sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:red-apple" /></template>
<style>
.ffqcrz2sg {
  fill: var(--svg-color--662113, #662113);
  d: path("M18 10a1 1 0 0 1-1-1c0-3.441 1.2-6.615 3.293-8.707a.999.999 0 1 1 1.414 1.414C19.986 3.427 19 6.085 19 9a1 1 0 0 1-1 1");
}

.q7vjvmbdo {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M24 7c-3 0-3 1-6 1s-3-1-6-1c-4 0-9 2-9 9c0 11 6 20 10 20c3 0 3-1 5-1s2 1 5 1c4 0 10-9 10-20c0-7.001-5-9-9-9");
}

.wut168b0z {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M19 7s3-4 8-4c4 0 6 2 6 2s-4 3-7 3s-7-1-7-1");
}

</style>
