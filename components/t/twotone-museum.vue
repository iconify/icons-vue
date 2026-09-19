<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om0y_1b2i"/><path class="hozlc6d5l"/><path class="z0jfpcbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-museum" /></template>
<style>
.hozlc6d5l {
  fill: currentColor;
  d: path("M22 11V9L12 2L2 9v2h2v9H2v2h20v-2h-2v-9zm-4 9H6V9h12z");
}

.om0y_1b2i {
  fill: currentColor;
  d: path("M6 20h12V9H6zm2-9h2l2 3l2-3h2v7h-2v-4l-2 3l-2-3v4H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z0jfpcbwl {
  fill: currentColor;
  d: path("m10 14l2 3l2-3v4h2v-7h-2l-2 3l-2-3H8v7h2z");
}

</style>
