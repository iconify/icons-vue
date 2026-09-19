<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="epebgbx0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:white-circle" /></template>
<style>
.epebgbx0r {
  cx: 32px;
  cy: 32px;
  r: 31px;
  fill: var(--svg-color--d0d2d3, #d0d2d3);
}

</style>
