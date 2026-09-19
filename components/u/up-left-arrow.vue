<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="kihf3zb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:up-left-arrow" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.kihf3zb8t {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.5 42.1L20 20l22.1-.5l-7.5 7.5l13.3 13.2l-7.3 7.3l-13.2-13.3z");
}

</style>
