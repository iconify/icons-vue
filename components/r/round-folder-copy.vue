<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyfbi6bqn"/><path class="gnqyzac9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-folder-copy" /></template>
<style>
.gnqyzac9d {
  fill: currentColor;
  d: path("M21 4h-7l-1.41-1.41c-.38-.38-.89-.59-1.42-.59H7c-1.1 0-1.99.9-1.99 2L5 15c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2");
}

.lyfbi6bqn {
  fill: currentColor;
  d: path("M2 6c-.55 0-1 .45-1 1v12c0 1.1.9 2 2 2h16c.55 0 1-.45 1-1s-.45-1-1-1H3V7c0-.55-.45-1-1-1");
}

</style>
