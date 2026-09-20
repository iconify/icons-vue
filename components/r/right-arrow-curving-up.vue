<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mna24bz3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:right-arrow-curving-up" /></template>
<style>
.mna24bz3w {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m70.1 77.57l4.77-8.73l24.52 13.39L84.5 30.06L32.53 45.71l24.55 13.41l-4.8 8.79c-2.56 4.68-7.21 8.37-13.03 8.84c-3.24.27-7.76-.94-10.56-2.48l-.08 21.97c7.62 2.41 28.06 5.93 41.49-18.67");
}

</style>
