<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9sdw3blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mustache-duotone" /></template>
<style>
.h9sdw3blv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.808C11.48 9.198 9.919 8.344 7.838 9.808C5.236 11.638 3.675 11.18 2.114 10.266C1.767 11.485 2.01 14.108 5.756 14.84C9.503 15.572 11.48 13.575 12 13.308C12.52 13.575 14.497 15.572 18.244 14.84C21.99 14.108 22.233 11.485 21.886 10.266C20.325 11.18 18.764 11.638 16.163 9.808C14.081 8.344 12.52 9.198 12 9.808Z");
}

</style>
