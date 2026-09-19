<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-sdrbtn"/><path class="avs9u3b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-cellular-2-bar" /></template>
<style>
.avs9u3b-n {
  fill: currentColor;
  d: path("M14 10L3.71 20.29c-.63.63-.19 1.71.7 1.71H14z");
}

.ld-sdrbtn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M4.41 22H20c1.1 0 2-.9 2-2V4.41c0-.89-1.08-1.34-1.71-.71L3.71 20.29c-.63.63-.19 1.71.7 1.71");
}

</style>
