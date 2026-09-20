<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8b2x4yrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remember-me-rounded" /></template>
<style>
.u8b2x4yrm {
  fill: currentColor;
  d: path("M7.616 22q-.667 0-1.141-.475T6 20.386V3.615q0-.666.475-1.14T7.615 2h8.77q.666 0 1.14.475T18 3.614v16.77q0 .666-.475 1.14t-1.14.475zM12 14q1.35 0 2.613.343t2.387.972V5.5H7v9.816q1.125-.631 2.388-.974T12 14m-1.77-2.228q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728");
}

</style>
