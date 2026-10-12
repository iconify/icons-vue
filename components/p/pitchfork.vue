<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0by6y0_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pitchfork" /></template>
<style>
.j0by6y0_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V11M7 2.75V7.5a3.5 3.5 0 0 0 3.5 3.5h3A3.5 3.5 0 0 0 17 7.5V2.75m-5 0V11");
}

</style>
