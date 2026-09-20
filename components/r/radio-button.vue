<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q3ncj0etc"/><circle class="nbtmwvp6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:radio-button" /></template>
<style>
.nbtmwvp6k {
  cx: 18px;
  cy: 18px;
  r: 8px;
  fill: var(--svg-color--bbddf5, #bbddf5);
}

.q3ncj0etc {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--269, #269);
}

</style>
