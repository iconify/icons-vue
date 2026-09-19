<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="aep4z1bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:up-down-arrow" /></template>
<style>
.aep4z1bdd {
  fill: var(--svg-color--fff, #fff);
  d: path("m32 52l16-15.5H36.6v-9H48L32 12L16 27.5h11.4v9H16z");
}

.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

</style>
