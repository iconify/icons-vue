<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzhg5bcvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:teacher" /></template>
<style>
.hzhg5bcvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12C9.5 13.3807 8.3807 14.5 7 14.5C5.6193 14.5 4.5 13.3807 4.5 12C4.5 10.6193 5.6193 9.5 7 9.5C8.3807 9.5 9.5 10.6193 9.5 12ZM4.5 18.5L9.5 18.5C10.8807 18.5 12 19.6193 12 21C12 21.5523 11.5523 22 11 22L3 22C2.4477 22 2 21.5523 2 21C2 19.6193 3.1193 18.5 4.5 18.5ZM9 5.8153L9 4C9 2.8954 9.8954 2 11 2L20 2C21.1046 2 22 2.8954 22 4L22 13C22 14.1046 21.1046 15 20 15L12.7663 15M13 6.5H18M14 10.5H18");
}

</style>
