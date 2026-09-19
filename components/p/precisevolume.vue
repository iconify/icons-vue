<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kwsqasgfr"/><path class="ed757gs9x"/><path class="jwvxl4bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:precisevolume" /></template>
<style>
.ed757gs9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.542 18.091a6 6 0 0 1 0 11.818");
}

.jwvxl4bxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.847 22.03a2 2 0 0 1 0 3.94M16.5 21.5v5h4l4 3.5V18l-4 3.5Z");
}

.kwsqasgfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.23 26a17 17 0 0 0 .14-2a17 17 0 0 0-.14-2l4.33-3.39a1 1 0 0 0 .25-1.31l-4.1-7.11a1 1 0 0 0-1.25-.44l-5.11 2.06a15.7 15.7 0 0 0-3.46-2l-.77-5.43a1 1 0 0 0-1-.86H19.9a1 1 0 0 0-1 .86l-.77 5.43a15.4 15.4 0 0 0-3.46 2L9.54 9.75a1 1 0 0 0-1.25.44l-4.1 7.11a1 1 0 0 0 .25 1.31L8.76 22a17 17 0 0 0-.14 2a17 17 0 0 0 .14 2l-4.32 3.39a1 1 0 0 0-.25 1.31l4.1 7.11a1 1 0 0 0 1.25.44l5.11-2.06a15.7 15.7 0 0 0 3.46 2l.77 5.43a1 1 0 0 0 1 .86h8.2a1 1 0 0 0 1-.86l.77-5.43a15.4 15.4 0 0 0 3.46-2l5.11 2.06a1 1 0 0 0 1.25-.44l4.1-7.11a1 1 0 0 0-.25-1.31Z");
}

</style>
