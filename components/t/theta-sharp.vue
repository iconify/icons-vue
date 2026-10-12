<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_yu4ob_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:theta-sharp" /></template>
<style>
.q_yu4ob_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c3.75 0 6.25 3.75 6.25 8.75s-2.5 8.75-6.25 8.75S5.75 17 5.75 12S8.25 3.25 12 3.25ZM8.75 12h6.5");
}

</style>
