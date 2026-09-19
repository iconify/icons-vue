<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smjt46b7k"/><path class="jtowclbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-hourglass-full" /></template>
<style>
.jtowclbnw {
  fill: currentColor;
  d: path("M18 2H6v6h.01L6 8.01L10 12l-4 4l.01.01H6V22h12v-5.99h-.01L18 16l-4-4l4-3.99l-.01-.01H18zm-2 14.5V20H8v-3.5l4-4zm0-9l-4 4l-4-4V4h8z");
}

.smjt46b7k {
  fill: currentColor;
  d: path("m8 7.5l4 4l4-4V4H8zm0 9V20h8v-3.5l-4-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
