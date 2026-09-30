<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a7urfewjw"/><path class="kztw_db4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stamp-fill" /></template>
<style>
.a7urfewjw {
  fill: currentColor;
  d: path("M15.1092 8.5165L15.769 11L17 11C19.7614 11 22 13.2386 22 16C22 17.1046 21.1046 18 20 18L4 18C2.8954 18 2 17.1046 2 16C2 13.2386 4.2386 11 7 11L8.231 11L8.8908 8.5165C8.3145 7.8044 8 6.9161 8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6C16 6.9161 15.6855 7.8044 15.1092 8.5165Z");
  stroke: none;
}

.kztw_db4s {
  d: path("M5 21L19 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
