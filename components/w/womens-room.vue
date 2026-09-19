<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><path class="nj1ra4hnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:womens-room" /></template>
<style>
.nj1ra4hnw {
  fill: var(--svg-color--fff, #fff);
  d: path("M36 23h-8c-1 0-2 1-2 2l-3 11h3l2-9v4l-2 9h2v11h3V40h2v11h3V40h2l-2-9v-4l2 9h3l-3-11c0-1-1-2-2-2m0-4c0 1-1 2-2 2h-4c-1 0-2-1-2-2v-4c0-1 1-2 2-2h4c1 0 2 1 2 2z");
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

</style>
