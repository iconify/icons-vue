<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7ifl8bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:social-security-contribution" /></template>
<style>
.q7ifl8bni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5V21m19-11.5V21m-19-9.5C6 19 18 19 21.5 11.5m-19 0h19m-15 0l2.25 4.75M12 11.5v5.75m5.5-5.75l-2.25 4.75M9.25 5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M12 4.25v1.5");
}

</style>
