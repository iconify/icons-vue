<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="cyhgp7ttu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:restroom" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.cyhgp7ttu {
  fill: var(--svg-color--fff, #fff);
  d: path("M46 23h-8c-1 0-2 1-2 2l-3 11h3l2-9v4l-2 9h2v11h3V40h2v11h3V40h2l-2-9v-4l2 9h3l-3-11c0-1-1-2-2-2m0-4c0 1-1 2-2 2h-4c-1 0-2-1-2-2v-4c0-1 1-2 2-2h4c1 0 2 1 2 2zm-18 4H16c-1 0-2 1-2 2l-1 11h3l1-9l1 24h3l1-13l1 13h3l1-24l1 9h3l-1-11c0-1-1-2-2-2m-2-4c0 1-1 2-2 2h-4c-1 0-2-1-2-2v-4c0-1 1-2 2-2h4c1 0 2 1 2 2z");
}

</style>
