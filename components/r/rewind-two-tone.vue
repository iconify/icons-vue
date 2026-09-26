<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v85bn7bst"/><path class="a01qzhb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rewind-two-tone" /></template>
<style>
.a01qzhb9v {
  d: path("M22 16.495037C22 17.809976 20.428429 18.488512 19.47137 17.586788L14.314246 12.727834C13.89525 12.333063 13.89525 11.666937 14.314246 11.272166L19.47137 6.413212C20.428429 5.511488 22 6.190024 22 7.504963ZM10 16.495037C10 17.809976 8.428429 18.488512 7.47137 17.586788L2.314246 12.727834C1.89525 12.333063 1.89525 11.666937 2.314246 11.272166L7.47137 6.413212C8.428429 5.511488 10 6.190024 10 7.504963Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v85bn7bst {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 16.495037C23 18.686603 20.380714 19.817496 18.785617 18.314623L13.628494 13.455669C12.790502 12.666127 12.790502 11.333873 13.628494 10.544331L18.785617 5.685378C20.380715 4.182505 23 5.313398 23 7.504964ZM11 16.495037C11 18.686603 8.380715 19.817496 6.785617 18.314623L1.628493 13.455669C0.790501 12.666127 0.790501 11.333873 1.628493 10.544331L6.785617 5.685377C8.380715 4.182504 11 5.313397 11 7.504963Z");
  stroke: none;
}

</style>
