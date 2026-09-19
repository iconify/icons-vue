<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stz9c2u3b"/><path class="qejra2b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-headphones" /></template>
<style>
.qejra2b6w {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 0-9 9v7c0 1.1.9 2 2 2h4v-8H5v-1c0-3.87 3.13-7 7-7s7 3.13 7 7v1h-4v8h4c1.1 0 2-.9 2-2v-7a9 9 0 0 0-9-9M7 15v4H5v-4zm12 4h-2v-4h2z");
}

.stz9c2u3b {
  fill: currentColor;
  d: path("M5 15h2v4H5zm12 0h2v4h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
