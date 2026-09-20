<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path class="z8kt29bqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wwy-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.z8kt29bqz {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.108 10.776a.43.43 0 0 1 0-.57a.345.345 0 0 1 .521 0l2.748 3.018a.44.44 0 0 1 0 .57a.344.344 0 0 1-.522 0zm7.442-.57a.44.44 0 0 1 0 .57l-2.748 3.018a.344.344 0 0 1-.521 0a.43.43 0 0 1 0-.57l2.747-3.018a.35.35 0 0 1 .404-.089q.068.031.118.088m.904.57a.43.43 0 0 1 0-.57a.345.345 0 0 1 .521 0l2.748 3.018a.44.44 0 0 1 0 .57a.344.344 0 0 1-.522 0zm7.442 0a.44.44 0 0 0 0-.57a.35.35 0 0 0-.405-.089a.4.4 0 0 0-.117.088l-2.747 3.019a.43.43 0 0 0 0 .57a.345.345 0 0 0 .521 0z");
}

</style>
