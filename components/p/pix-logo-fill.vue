<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z9fwhh1-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pix-logo-fill" /></template>
<style>
.z9fwhh1-r {
  fill: currentColor;
  d: path("m235.34 139.28l-19.56 19.55A4 4 0 0 1 213 160h-41.68l-32-32l32-32H213a4 4 0 0 1 2.82 1.17l19.56 19.55a16 16 0 0 1-.04 22.56M67.05 80H88a8 8 0 0 1 5.65 2.34L128 116.68l34.35-34.34A8 8 0 0 1 168 80h21a4 4 0 0 0 2.83-6.83l-52.5-52.51a16 16 0 0 0-22.56 0L64.22 73.17A4 4 0 0 0 67.05 80M189 176h-21a8 8 0 0 1-5.65-2.34L128 139.31l-34.35 34.35A8 8 0 0 1 88 176H67a4 4 0 0 0-2.83 6.83l52.5 52.51a16 16 0 0 0 22.56 0l52.5-52.51A4 4 0 0 0 189 176m-72.26-48l-32-32H43a4 4 0 0 0-2.82 1.17l-19.52 19.55a16 16 0 0 0 0 22.56l19.56 19.55A4 4 0 0 0 43 160h41.68Z");
}

</style>
