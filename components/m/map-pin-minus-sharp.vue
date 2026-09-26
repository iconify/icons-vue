<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5rba1iag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-minus-sharp" /></template>
<style>
.f5rba1iag {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.2546 22.2847L5.0372 15.3333C3.7253 13.8666 3 11.9678 3 10C3 5.5817 6.5817 2 11 2C15.4183 2 19 5.5817 19 10C19 10.6747 18.9146 11.3467 18.746 12L18.496 12.9683M14 10C14 11.6569 12.6569 13 11 13C9.3431 13 8 11.6569 8 10C8 8.3431 9.3431 7 11 7C12.6569 7 14 8.3431 14 10ZM14 19L22 19");
}

</style>
