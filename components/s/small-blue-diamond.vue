<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kb7szzbxi"/><path class="fivazkjdu"/><path class="p62azid2n"/><circle class="dt21z_-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:small-blue-diamond" /></template>
<style>
.dt21z_-yh {
  cx: 46.8px;
  cy: 62.7px;
  r: 1.2px;
  fill: var(--svg-color--90caf9, #90caf9);
}

.fivazkjdu {
  fill: var(--svg-color--2196f3, #2196f3);
  d: path("M62.9 46.1L79 62.2c.9 1 .9 2.5-.1 3.4l-16 16.2c-1 1-2.5 1-3.5 0L43.3 65.7c-1-.9-1-2.5-.1-3.4l16.2-16.1c1-1 2.5-1 3.5-.1");
}

.kb7szzbxi {
  fill: var(--svg-color--1976d2, #1976d2);
  d: path("m65.9 43.5l18.5 18.4c1.1 1.1 1 2.9-.1 3.9L65.9 84.4c-1.1 1.1-2.9 1.1-4 0L43.5 65.9a2.81 2.81 0 0 1-.1-3.9l18.5-18.4c1.1-1.2 2.9-1.2 4-.1");
}

.p62azid2n {
  fill: var(--svg-color--90caf9, #90caf9);
  d: path("M60 47.5c-.5.4-11.7 11.5-11.7 11.5s-.9.8-.3 1.7c.6.8 1.5.4 2 0s10.5-10.3 10.9-10.8s.5-1.4.2-1.9c-.2-.7-.7-.7-1.1-.5");
}

</style>
