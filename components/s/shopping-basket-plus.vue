<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgl3k5bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-basket-plus" /></template>
<style>
.mgl3k5bkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21L6.4817 21C5.6015 21 4.8248 20.4246 4.5684 19.5826L2.0437 11.2913C1.848 10.6488 2.3287 10 3.0003 10L20.9997 10C21.5692 10 22.0014 10.4664 22.0004 11M9 10L9.8773 3.8586C9.9477 3.3659 10.3696 3 10.8673 3L14.847 3C15.4555 3 15.923 3.539 15.8369 4.1414L15 10M19 15V21M16 18H22");
}

</style>
