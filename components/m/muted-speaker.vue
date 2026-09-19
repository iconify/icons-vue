<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><circle class="ketqe1bnq"/><path class="s3380kb9l"/><path class="c9_z_eb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:muted-speaker" /></template>
<style>
.c9_z_eb-q {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("m9.23 13.474l4.243-4.242l41.294 41.294l-4.242 4.243z");
}

.ketqe1bnq {
  cx: 32px;
  cy: 32px;
  r: 24px;
  fill: var(--svg-color--333, #333);
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.s3380kb9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M41.5 28.1V13.9c0-.5-.4-.9-.9-.9s-.9.4-.9.9v.5l-14.1 9.9h-6.2c-1.2 0-2.3.9-2.3 2.1v11.3c0 1.2 1 2.1 2.3 2.1h6.2l14.1 9.9v.5c0 .5.4.9.9.9s.9-.4.9-.9V36c2.3 0 4.2-1.7 4.2-3.9s-1.9-4-4.2-4");
}

</style>
