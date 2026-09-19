<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="lo697yzva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:right-arrow-curving-down" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.lo697yzva {
  fill: var(--svg-color--fff, #fff);
  d: path("M40.4 45.1V22.9c0-7.1-5.6-12.9-12.5-12.9c-3.3 0-6.5 1.3-8.9 3.8l5.1 5.2c1-1 2.4-1.6 3.8-1.6c3 0 5.4 2.5 5.4 5.5v22.2h-4.6l8.2 8.9l8.2-8.9z");
}

</style>
