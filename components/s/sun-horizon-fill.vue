<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g736b4bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-horizon-fill" /></template>
<style>
.g736b4bua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 15C7.5 12.515 9.515 10.5 12 10.5C14.485 10.5 16.5 12.515 16.5 15M2 15H3.5M20.5 15H22M4.929 7.929L5.99 8.99M19.071 7.929L18.01 8.99M12 6.5V5M4 19H20");
}

</style>
