<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byhjt7b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-lounger" /></template>
<style>
.byhjt7b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20L21 20M6 20L6 22M6 20L4 17M18 20L18 22M12 11.6C9.5 9 5 9.5 3 11.6C3 9.6 4.575 7.8 6.4875 6.2C8.4 4.6 10.65 3.2 12 2C13.35 3.2 15.6 4.6 17.5125 6.2C19.425 7.8 21 9.6 21 11.6C18.5 9 14 9.5 12 11.6ZM12 11.6L12 20");
}

</style>
