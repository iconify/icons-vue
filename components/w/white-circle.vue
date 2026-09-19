<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="o84it3bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:white-circle" /></template>
<style>
.o84it3bmf {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

</style>
