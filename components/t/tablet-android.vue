<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do8qz1bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-android" /></template>
<style>
.do8qz1bwy {
  fill: currentColor;
  d: path("M5.616 22q-.667 0-1.141-.475T4 20.386V3.615q0-.666.475-1.14T5.615 2h12.77q.666 0 1.14.475T20 3.614v16.77q0 .666-.475 1.14t-1.14.475zm4.615-2.346h3.538v-.77h-3.538zM5 16.538h14V5.5H5z");
}

</style>
