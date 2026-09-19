<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cqp4v_i5f"/><path class="cti5nr_-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:up-left-arrow" /></template>
<style>
.cqp4v_i5f {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.873 56.802a6.863 6.863 0 0 1-6.862 6.868H7.067a6.864 6.864 0 0 1-6.86-6.868V6.864A6.863 6.863 0 0 1 7.067 0H57.01a6.86 6.86 0 0 1 6.862 6.864z");
}

.cti5nr_-y {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.264 40.451l-2.192-24.21l24.2 1.263c1.705 1.917 1.964 4.541.519 6.05l-2.452 2.556l11.997 11.506a5.07 5.07 0 0 1 .15 7.166l-4.552 4.743a5.067 5.067 0 0 1-7.165.146L24.775 38.164l-2.45 2.554c-1.444 1.502-4.068 1.359-6.06-.262");
}

</style>
