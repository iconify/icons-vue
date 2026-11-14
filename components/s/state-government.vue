<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_hnq3pco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:state-government" /></template>
<style>
.v_hnq3pco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h18v8H3Zm3.5 0a5.5 5.5 0 0 1 11 0M12 7.5v-4M7.5 15.75V21m4.5-5.25V21m4.5-5.25V21");
}

</style>
