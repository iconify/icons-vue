<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4d9x043x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:towel-rack" /></template>
<style>
.z4d9x043x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7H9M20 7H22M20 7C20 4.79 18.2091 3 16 3H6.5M20 7V13V17M9 15H6C4.8954 15 4 14.1 4 13V5.5C4 4.12 5.1193 3 6.5 3M9 15V13V5.5C9 4.12 7.8807 3 6.5 3M9 15V17M9 17V19C9 20.1 9.8954 21 11 21H18C19.1046 21 20 20.1 20 19V17M9 17H20");
}

</style>
