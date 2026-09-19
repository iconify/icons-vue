<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm7wv141s"/><path class="vlijg79bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-settings-brightness" /></template>
<style>
.pm7wv141s {
  fill: currentColor;
  d: path("M3 19.01h18V4.99H3zm5-8.51V8h2.5L12 6.5L13.5 8H16v2.5l1.5 1.5l-1.5 1.5V16h-2.5L12 17.5L10.5 16H8v-2.5L6.5 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vlijg79bc {
  fill: currentColor;
  d: path("M8 16h2.5l1.5 1.5l1.5-1.5H16v-2.5l1.5-1.5l-1.5-1.5V8h-2.5L12 6.5L10.5 8H8v2.5L6.5 12L8 13.5zm4-7c1.66 0 3 1.34 3 3s-1.34 3-3 3zm9-6H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16.01H3V4.99h18z");
}

</style>
