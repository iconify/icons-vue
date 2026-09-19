<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz60y4b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-pin-drop" /></template>
<style>
.xz60y4b6m {
  fill: currentColor;
  d: path("M6 20h12c.55 0 1 .45 1 1s-.45 1-1 1H6c-.55 0-1-.45-1-1s.45-1 1-1m6-13c-1.1 0-2 .9-2 2s.9 2 2 2s2-.9 2-2s-.9-2-2-2m0-5c3.27 0 7 2.46 7 7.15c0 2.98-2.13 6.12-6.39 9.39c-.36.28-.86.28-1.22 0Q5 13.62 5 9.15C5 4.46 8.73 2 12 2");
}

</style>
