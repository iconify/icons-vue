<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofuzzgbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slash-forward-20-filled" /></template>
<style>
.ofuzzgbnx {
  fill: currentColor;
  d: path("M13.016 2.049a.75.75 0 0 1 .435.967l-5.5 14.5a.75.75 0 1 1-1.402-.532l5.5-14.5a.75.75 0 0 1 .967-.435");
}

</style>
