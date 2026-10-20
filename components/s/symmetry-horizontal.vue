<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw_bv_w_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-horizontal" /></template>
<style>
.kw_bv_w_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.6832 5L16.3168 5C16.7288 5 17.0986 5.2527 17.2484 5.6365L21.9307 17.6365C22.1865 18.2922 21.7029 19 20.9991 19L3.0009 19C2.2971 19 1.8135 18.2922 2.0694 17.6365L6.7516 5.6365C6.9014 5.2527 7.2712 5 7.6832 5ZM12 2L12 22");
}

</style>
