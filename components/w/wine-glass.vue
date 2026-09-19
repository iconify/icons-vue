<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="p8lb5hymc"/><path class="oja6n1bts"/><path class="r4fogkclo"/><path class="o4w6zn9pz"/><path class="abqwnokec"/><path class="nrht3ib7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:wine-glass" /></template>
<style>
.abqwnokec {
  fill: var(--svg-color--df2c43, #df2c43);
  d: path("M33.16 15.91c-6.62.002-14.874-2.494-14.766-4.609s5.395-4.613 14.766-4.613c9.369 0 14.767 2.607 14.767 4.613c0 2.01-7.935 4.607-14.767 4.609");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.nrht3ib7d {
  fill: var(--svg-color--e37180, #e37180);
  d: path("M33.16 6.688c-9.291 0-14.561 2.456-14.756 4.559a16.674 7.633 0 0 0 14.791 4.115a16.674 7.633 0 0 0 14.73-4.064c-.007-2.01-5.402-4.61-14.766-4.61");
}

.o4w6zn9pz {
  fill: var(--svg-color--bac4c9, #bac4c9);
  fill-opacity: var(--svg-fill-opacity--0-627, 0.627);
  d: path("M34.608 58.642c0 .646-.601 1.174-1.346 1.174s-1.345-.527-1.345-1.174v-22.15c0-.647.601-1.174 1.346-1.174s1.346.527 1.346 1.174v22.15");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.oja6n1bts {
  fill: var(--svg-color--bac4c9, #bac4c9);
  fill-opacity: var(--svg-fill-opacity--0-627, 0.627);
  d: path("M33.2.094a16.674 7.633 0 0 0-16.057 5.611a16.674 7.633 0 0 0-.002.004c-.473.485-.696 1.449-.696 3.121c0 7.653-7.543 26.675 16.705 28.44c24.11-1.494 16.705-20.783 16.705-28.44c0-.256-.018-.454-.029-.678a16.674 7.633 0 0 0 .047-.423A16.674 7.633 0 0 0 33.199.094");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.p8lb5hymc {
  cx: 33.15px;
  cy: 59.818px;
  fill: var(--svg-color--bac4c9, #bac4c9);
  fill-opacity: var(--svg-fill-opacity--0-628, 0.628);
  opacity: var(--svg-opacity--0-7, 0.7);
  rx: 15.539px;
  ry: 4.181px;
}

.r4fogkclo {
  fill: var(--svg-color--8a0000, #8a0000);
  d: path("M33.16 11.37c-9.372 0-14.783-1.837-14.766.217c0 5.955-5.452 21.13 14.766 22.89c20.321-1.627 14.767-16.935 14.767-22.89c-.041-1.887-5.395-.217-14.767-.217");
}

</style>
