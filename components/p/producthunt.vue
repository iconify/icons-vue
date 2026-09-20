<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGYqDZydAw" x1="50%" x2="50%" y1="0%" y2="100%"><stop offset="0%" class="j4cv81v0h"/><stop offset="100%" class="rbzyirh3h"/></linearGradient></defs><g class="bi12bsetm"><path fill="url(#SVGYqDZydAw)" class="x9xkurbap"/><path class="ks4-4obkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:producthunt" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.j4cv81v0h {
  stop-color: var(--svg-color--da552f, #da552f);
}

.ks4-4obkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M96 76.8v102.4h19.2v-32h29.056c19.296-.512 34.944-16.16 34.944-35.2c0-19.552-15.648-35.2-34.944-35.2zm48.493 51.2H115.2V96h29.293c8.563 0 15.507 7.168 15.507 16s-6.944 16-15.507 16");
}

.rbzyirh3h {
  stop-color: var(--svg-color--d04b25, #d04b25);
}

.x9xkurbap {
  d: path("M128 256c70.694 0 128-57.306 128-128S198.694 0 128 0S0 57.306 0 128s57.306 128 128 128");
}

</style>
