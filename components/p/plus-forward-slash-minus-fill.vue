<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqldsy3sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plus-forward-slash-minus-fill" /></template>
<style>
.zqldsy3sa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 18H22M2 6H5.9986M5.9986 6H10M5.9986 6L5.9971 10M5.9986 6L6 2M5 22L19 2");
}

</style>
