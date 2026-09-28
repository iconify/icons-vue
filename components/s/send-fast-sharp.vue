<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eruqslbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-fast-sharp" /></template>
<style>
.eruqslbhu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 2L17.2802 17.9523L12.7229 11.2771L6.0477 6.7198L22 2ZM12.7229 11.2771L22 2M1.7071 22.2929L6.7929 17.2071M1.7071 16.2929L5.7929 12.2071M7.7071 22.2929L11.7929 18.2071");
}

</style>
