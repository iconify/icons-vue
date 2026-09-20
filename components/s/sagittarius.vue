<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="ficpovbga"/><circle class="ccliwtbqi"/><path class="ho_qqfbkv"/><path class="z8plbccyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sagittarius" /></template>
<style>
.ccliwtbqi {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--1976d2, #1976d2);
}

.ficpovbga {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--0d47a1, #0d47a1);
}

.ho_qqfbkv {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.3 3-17.9 6.4-23.1 14.3c-2 3-4.9 14.4-8.6 12.3c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z8plbccyh {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M92 34H64.2c-2.1 0-4 1.5-4.2 3.6c-.2 2.4 1.7 4.4 4 4.4h15.8c.9 0 1.3 1.1.7 1.7L59 64.8c-.8.8-2 .8-2.8 0l-9.7-9.6c-1.6-1.6-4.1-1.6-5.7 0s-1.6 4.1 0 5.7l9.7 9.6c.8.8.8 2.1 0 2.8L33.3 91c-1.5 1.5-1.8 4.1-.3 5.7c1.5 1.7 4.2 1.8 5.8.2l17.5-18c.8-.8 2-.8 2.8 0l10.1 10c1.6 1.6 4.1 1.6 5.7 0s1.6-4.1 0-5.7l-10.1-10c-.8-.8-.8-2.1 0-2.8l21.6-21.1c.6-.6 1.7-.2 1.7.7v15.9c0 2.1 1.5 3.9 3.6 4.2c2.4.2 4.4-1.6 4.4-4V38c-.1-2.2-1.9-4-4.1-4");
}

</style>
