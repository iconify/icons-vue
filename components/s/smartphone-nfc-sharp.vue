<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwfb-rv9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-nfc-sharp" /></template>
<style>
.pwfb-rv9r {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L12 4L12 20L2 20ZM5 8L6 8L8 8L9 8M17.1101 7.552L17.4283 8.5C17.8069 9.6281 18 10.8101 18 12C18 13.1899 17.8069 14.3719 17.4283 15.5L17.1101 16.448M21.0091 6.5461L21.3091 7.5C21.767 8.9561 22 10.4736 22 12C22 13.5264 21.767 15.0439 21.3091 16.5L21.0091 17.4539");
}

</style>
