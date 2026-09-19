<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zbiulj3ix"/><path id="SVGUaiSMepI" class="aduvc6nlk"/><use href="#SVGUaiSMepI"/><path class="npox17bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:shooting-star" /></template>
<style>
.aduvc6nlk {
  fill: var(--svg-color--fff, #fff);
  d: path("m38.9 39.9l10.9-7.8H36.3l-4.2-12.6L28 32.1H14.5l10.9 7.8l-4.1 12.6l10.8-7.8L43 52.5z");
}

.npox17bvx {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M39 28.4h3.5L57 2L37.8 24.7zM57 2L34.6 15l1.8 5.6zm-3.1 26.4L57 2l-9.8 26.4z");
}

.zbiulj3ix {
  fill: var(--svg-color--f5a300, #f5a300);
  d: path("m7 31l14.1 10.3L14.2 62l17.9-12.8l18 12.8L57 2z");
}

</style>
