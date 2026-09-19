<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-sdrbtn"/><path class="oyg08bbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-cellular-3-bar" /></template>
<style>
.ld-sdrbtn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M4.41 22H20c1.1 0 2-.9 2-2V4.41c0-.89-1.08-1.34-1.71-.71L3.71 20.29c-.63.63-.19 1.71.7 1.71");
}

.oyg08bbui {
  fill: currentColor;
  d: path("M17 7L3.71 20.29c-.63.63-.19 1.71.7 1.71H17z");
}

</style>
