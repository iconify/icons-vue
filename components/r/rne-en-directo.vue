<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="wi1qb2_ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rne-en-directo" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.wi1qb2_ot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 20.648a4.327 4.327 0 0 1 4.315-4.315m-4.315 0v11.434m15.177 0v-7.12a4.327 4.327 0 0 0-4.315-4.314a4.327 4.327 0 0 0-4.315 4.315v7.12m0-7.12v-4.315m21.585 12.441c-.868 1.736-2.893 2.893-4.918 2.893c-3.183 0-5.787-2.604-5.787-5.786v-3.762c0-3.182 2.604-5.786 5.786-5.786c3.183 0 5.787 2.604 5.787 5.786v2.026H26.927");
}

</style>
