<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5_amyb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:social-security-contribution" /></template>
<style>
.y5_amyb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5V21m19-11.5V21m-19-9.5C6 19 18 19 21.5 11.5m-19 0h19m-15 0l2.25 4.75M12 11.5v5.75m5.5-5.75l-2.25 4.75M9.25 5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM12 4.25v1.5");
}

</style>
