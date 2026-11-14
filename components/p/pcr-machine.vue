<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eghujgy1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pcr-machine" /></template>
<style>
.eghujgy1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 12h12.75A2.625 2.625 0 0 1 21 14.625v4.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-4.25A2.625 2.625 0 0 1 5.625 12M4.432 9.367l11.929-4.899A1.267 1.267 0 0 1 18 5.125a1.16 1.16 0 0 1-.653 1.557L5.444 11.146A1.184 1.184 0 0 1 4 10.625a.885.885 0 0 1 .432-1.258M7.5 15.25h.01m4.49 0h.01m4.49 0h.01M7.5 18.5h.01m4.49 0h.01m4.49 0h.01");
}

</style>
