<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5sk0r8_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translate-linear" /></template>
<style>
.v5sk0r8_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7895 17.667L11.5263 21M12.7895 17.667H19.7368M12.7895 17.667L14.01 14.446M19.7368 17.667L21 21M19.7368 17.667L17.5314 11.847C17.3389 11.339 16.8316 11 16.2632 11C15.6948 11 15.1874 11.339 14.9949 11.847L14.01 14.446M14.01 14.446C12.5485 14.189 10.45 13.047 8.632 11.601M8.632 11.601C6.6549 13.247 4.4429 14.5 3 14.5M8.632 11.601C7.1993 10.461 5.9408 9.133 5.3056 7.9M8.632 11.601C10.5068 10.039 13 7.756 13 5.199M13 5.199C11.7779 5.338 10.0814 5.5 8.7895 5.5C6.5192 5.5 3 5 3 5M13 5.199C13.9254 5.093 14.5789 5 14.5789 5M8.2632 3H9.3158");
}

</style>
