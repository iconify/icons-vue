<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="b-qwdpb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:play-or-pause-button" /></template>
<style>
.b-qwdpb8m {
  fill: var(--svg-color--fff, #fff);
  d: path("m13 16l19 16l-19 16zm22.8 0h5.7v32h-5.7zm9.5 0H51v32h-5.7z");
}

.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

</style>
