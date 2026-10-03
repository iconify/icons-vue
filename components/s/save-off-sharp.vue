<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1-l24bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-off-sharp" /></template>
<style>
.c1-l24bnk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 21L3 21L3 3M14.8715 14.8715C14.4981 16.1033 13.3538 17 12 17C10.3431 17 9 15.6569 9 14C9 12.6462 9.8967 11.5019 11.1285 11.1285M7.6569 3L17 3L21 7L21 16.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
