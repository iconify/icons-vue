<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="h9b-ws7bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:up-right-arrow" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.h9b-ws7bm {
  fill: var(--svg-color--fff, #fff);
  d: path("M44.5 42.1L44 20l-22.1-.5l7.5 7.5l-13.3 13.2l7.3 7.3l13.2-13.3z");
}

</style>
