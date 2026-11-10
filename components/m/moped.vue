<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acqcwbbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moped" /></template>
<style>
.acqcwbbsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16.5C4 17.88 5.1193 19 6.5 19C7.8807 19 9 17.88 9 16.5M2 16H12.4414C12.7394 16 12.974 15.74 12.994 15.44C13.1115 13.7 14.3906 10.34 18.3884 10.02C18.7029 10 18.9423 9.71 18.8804 9.4L18.0804 5.4C18.0336 5.17 17.8284 5 17.5901 5H15M3 16V14C3 11.79 4.7909 10 7 10H9.5C9.7761 10 10 10.22 10 10.5V13V16M10 6H6M19.5 19C18.1193 19 17 17.88 17 16.5C17 15.12 18.1193 14 19.5 14C20.8807 14 22 15.12 22 16.5C22 17.88 20.8807 19 19.5 19Z");
}

</style>
