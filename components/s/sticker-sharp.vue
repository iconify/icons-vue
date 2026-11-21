<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prpv6bc7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticker-sharp" /></template>
<style>
.prpv6bc7c {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 12C22 6.4772 17.5228 2 12 2C6.4772 2 2 6.4772 2 12C2 17.5228 6.4772 22 12 22ZM22 12C21.3475 11.8374 20.6776 11.7552 20.0052 11.7552C15.4489 11.7552 11.7552 15.4489 11.7552 20.0052C11.7552 20.6776 11.8374 21.3475 12 22M22 12L12 22");
}

</style>
