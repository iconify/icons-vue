<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2c_x7bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:snowflake" /></template>
<style>
.b2c_x7bdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.6795 12L19.3205 12M22 14.6795L19.3205 12L22 9.3205M2 9.3205L4.6795 12L2 14.6795M8.3397 5.6603L15.6603 18.3397M14.6795 22L15.6603 18.3397L19.3205 19.3205M9.3205 2L8.3397 5.6603L4.6795 4.6795M15.6603 5.6603L8.3397 18.3397M4.6795 19.3205L8.3397 18.3397L9.3205 22M19.3205 4.6795L15.6603 5.6603L14.6795 2");
}

</style>
