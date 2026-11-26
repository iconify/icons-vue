<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn9t1eb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:swords-sharp" /></template>
<style>
.qn9t1eb0k {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.7322 15.7322L15.9874 4.4771L21.0005 2.9995L19.5229 8.0126L8.2678 19.2678ZM2.7071 13.7071L3 14L10 21L10.2929 21.2929M6.5 17.5L3 21L2.7071 21.2929M9.4645 5.9289L9.1716 5.636L8.0125 4.477L2.9995 2.9995L4.477 8.0125L5.636 9.1716L5.9289 9.4645M15.5355 12L19.2678 15.7322L15.7322 19.2678L12 15.5355M21.2929 13.7071L21 14L14 21L13.7071 21.2929M17.5 17.5L21 21L21.2929 21.2929");
}

</style>
