<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imgpjccuu"/><path class="pj6ewyu5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-ios-share" /></template>
<style>
.imgpjccuu {
  fill: currentColor;
  d: path("M18 8h-3v2h3v11H6V10h3V8H6c-1.11 0-2 .89-2 2v11a2 2 0 0 0 2 2h12c1.1 0 2-.9 2-2V10a2 2 0 0 0-2-2");
}

.pj6ewyu5x {
  fill: currentColor;
  d: path("M11 16h2V5h3l-4-4l-4 4h3z");
}

</style>
