<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz56p_piq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-width-fill" /></template>
<style>
.iz56p_piq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 5V4C4 2.8954 4.8954 2 6 2H18C19.1046 2 20 2.8954 20 4V5M12 2V12M8.5 12H15.5M20 19H4M17 16L20 19L17 22M7 16L4 19L7 22");
}

</style>
