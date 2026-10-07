<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz5e3013z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:signature-sharp" /></template>
<style>
.pz5e3013z {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.8674 21.5025C3.0613 19.4211 4.7128 16.0493 5.9929 13.2135M5.99294 13.2135C8.20397 8.31533 9.7023 3.51693 7.5814 3.05055C3.63084 2.18185 2.58008 12.7908 5.99294 13.2135ZM5.99294 13.2135C6.19638 13.2387 6.41568 13.2277 6.65116 13.1759C10.8372 12.2554 11.3023 8.57347 11.7674 10.4144C12.2326 12.2554 13.1628 14.0964 14.5581 13.6361C15.9535 13.1759 16.4186 10.8747 17.3488 12.2554C18.2791 13.6361 20.6047 13.6361 22 13.6361L23 13.6361M7.5 18L23 18");
}

</style>
