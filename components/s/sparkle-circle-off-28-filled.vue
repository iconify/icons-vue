<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="du5iwrb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-off-28-filled" /></template>
<style>
.du5iwrb_m {
  fill: currentColor;
  d: path("M24.72 2.22a.75.75 0 1 1 1.06 1.06l-2.784 2.783A11.95 11.95 0 0 1 26 14c0 6.627-5.373 12-12 12a11.95 11.95 0 0 1-7.937-3.004L3.28 25.78a.75.75 0 0 1-1.06-1.06zm-6.395 12.363c-.275-.777-1.374-.777-1.65 0l-.4 1.132a.92.92 0 0 1-.56.56l-1.132.4c-.777.275-.777 1.375 0 1.65l1.133.4a.92.92 0 0 1 .56.56l.4 1.132c.275.777 1.374.777 1.65 0l.4-1.133a.92.92 0 0 1 .56-.56l1.131-.4c.777-.275.777-1.374 0-1.65l-1.132-.4a.92.92 0 0 1-.558-.56zM14 2c2.5 0 4.821.765 6.743 2.073l-6.137 6.138l-.81-.286a1.18 1.18 0 0 1-.72-.72L12.56 7.75c-.354-1-1.767-.999-2.12.001l-.514 1.454a1.18 1.18 0 0 1-.72.72l-1.456.516c-1 .353-1 1.767 0 2.12l1.456.515c.336.12.6.384.72.72l.286.81l-6.139 6.138A11.94 11.94 0 0 1 2 14C2 7.373 7.373 2 14 2");
}

</style>
