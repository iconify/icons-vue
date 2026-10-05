<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ranojpb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-shield-sharp" /></template>
<style>
.ranojpb_t {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3432 10 6 8.6569 6 7C6 5.3431 7.3432 4 9 4ZM11 21L2 21L2 20C2 16.6863 4.6863 14 8 14L10 14C10.2868 14 10.5733 14.0206 10.8571 14.0615M22 13.6976L22 18.2779L21.3928 19.0631C20.8667 19.7434 20.0327 20.5058 18.863 20.9355C18.6288 21.0215 18.3712 21.0215 18.137 20.9355C16.9673 20.5058 16.1333 19.7434 15.6073 19.0631L15 18.2778L15 13.6976L15.5173 13.6362C16.6758 13.4988 17.5504 12.9203 18.0731 12.4132C18.2974 12.1956 18.7026 12.1956 18.9269 12.4132C19.4496 12.9203 20.3242 13.4988 21.4827 13.6362Z");
}

</style>
