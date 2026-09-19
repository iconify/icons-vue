<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="oewamk3vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:next-track-button" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.oewamk3vi {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 18l17.4 14L12 46zm17.4 0l17.4 14l-17.4 14zm17.4 0H52v28h-5.2z");
}

</style>
