<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcp0yebys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-dot-sharp" /></template>
<style>
.kcp0yebys {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 3C20.6569 3 22 4.3431 22 6C22 7.6569 20.6569 9 19 9C17.3431 9 16 7.6569 16 6C16 4.3431 17.3431 3 19 3ZM13.3766 3.0559C12.4078 3.005 12.2039 3 12 3C6.4772 3 2 6.5817 2 11C2 12.9769 2.915 14.8839 4.5686 16.353L5 21L9.5808 18.7624C10.3721 18.9202 11.1845 19 12 19C16.674 19 20.6988 16.4142 21.9354 11.9329");
}

</style>
