<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nubbljb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-zap-sharp" /></template>
<style>
.nubbljb_b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.2929 3.7071L17 7L21 7L17.7071 10.2929M9 14L11 14C14.3137 14 17 16.6863 17 20L17 21L3 21L3 20C3 16.6863 5.6863 14 9 14ZM10 4C11.6569 4 13 5.3431 13 7C13 8.6569 11.6569 10 10 10C8.3431 10 7 8.6569 7 7C7 5.3431 8.3431 4 10 4Z");
}

</style>
