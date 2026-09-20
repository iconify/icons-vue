<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="o0rdm5brw"/><path class="pqyb9k48s"/><path class="ftkc7bbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:prohibited" /></template>
<style>
.ftkc7bbwm {
  fill: var(--svg-color--db4437, #db4437);
  d: path("m111.37 103.73l-8.43 8.41l-86.31-85.73L25.06 18z");
}

.o0rdm5brw {
  cx: 64.25px;
  cy: 64.28px;
  r: 54.44px;
  fill: var(--svg-color--fff, #fff);
}

.pqyb9k48s {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M63.99 128.01c-35.29 0-64-28.71-64-64s28.71-64 64-64s64 28.71 64 64s-28.71 64-64 64m0-117.11c-29.29 0-53.11 23.83-53.11 53.11c0 29.29 23.83 53.11 53.11 53.11S117.1 93.3 117.1 64.01c0-29.28-23.83-53.11-53.11-53.11");
}

</style>
