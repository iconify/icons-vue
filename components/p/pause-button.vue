<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="z5pnvwbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pause-button" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.z5pnvwbbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 14h8v36h-8zm16 0h8v36h-8z");
}

</style>
