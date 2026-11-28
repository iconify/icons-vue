<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ozqf44bug"/><path class="c5yb8bdcb"/><path clip-rule="evenodd" class="m6hdizbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-alert-duotone" /></template>
<style>
.c5yb8bdcb {
  d: path("M12 7V13");
}

.m6hdizbcy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 17C13 17.552 12.552 18 12 18C11.448 18 11 17.552 11 17C11 16.448 11.448 16 12 16C12.552 16 13 16.448 13 17Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozqf44bug {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.065 4.175C7.451 3.892 9.251 2.7 10.328 1.655C10.769 1.228 11.382 1 12 1C12.618 1 13.231 1.228 13.672 1.655C14.749 2.7 16.55 3.892 18.935 4.175C20.094 4.313 21 5.255 21 6.383V12.571C21 14.566 20.639 16.586 19.403 18.185C18.108 19.859 16.054 21.733 13.175 22.791C12.417 23.07 11.583 23.07 10.825 22.791C7.946 21.733 5.892 19.859 4.597 18.185C3.361 16.586 3 14.566 3 12.571V6.383C3 5.255 3.906 4.313 5.065 4.175Z");
  stroke: none;
}

</style>
