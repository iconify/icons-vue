<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l7m-g-svw"/><path class="rsrhfac5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-off-fill" /></template>
<style>
.l7m-g-svw {
  fill: currentColor;
  d: path("M10.8076 13.1924C11.8136 14.1984 12.9779 15.0324 14.2541 15.6612L14.6 15.2C15.1666 14.4446 16.0557 14 17 14L20 14C21.6569 14 23 15.3431 23 17L23 20C23 21.6569 21.6569 23 20 23C14.9609 23 10.1282 20.9982 6.565 17.435ZM4.6122 15.1452C2.2642 11.9034 1 8.0028 1 4C1 2.3431 2.3431 1 4 1L7 1C8.6569 1 10 2.3431 10 4L10 7C10 7.9443 9.5554 8.8334 8.8 9.4L8.3388 9.7459C8.5202 10.1141 8.719 10.4735 8.9344 10.823Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

</style>
