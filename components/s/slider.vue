<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l32rykfxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider" /></template>
<style>
.l32rykfxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 18C20 16.34 18.6569 15 17 15H15C13.3431 15 12 16.34 12 18M20 18C20 19.66 18.6569 21 17 21H15C13.3431 21 12 19.66 12 18M20 18H22M12 18H2M2 5V9C2 10.1 2.8954 11 4 11H8C9.1046 11 10 10.1 10 9V5C10 3.9 9.1046 3 8 3H4C2.8954 3 2 3.9 2 5ZM22 7C22 4.79 20.2091 3 18 3C15.7909 3 14 4.79 14 7C14 9.21 15.7909 11 18 11C20.2091 11 22 9.21 22 7Z");
}

</style>
