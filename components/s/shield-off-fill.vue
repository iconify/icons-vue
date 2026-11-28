<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="rlsmecc9r"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-off-fill" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rlsmecc9r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.853 18.853C17.554 20.338 15.675 21.872 13.175 22.791C12.417 23.07 11.583 23.07 10.825 22.791C7.946 21.733 5.892 19.859 4.597 18.185C3.361 16.586 3 14.566 3 12.571V6.383C3 5.495 3.562 4.722 4.366 4.366L18.853 18.853ZM8.637 4.394C8.449 4.207 8.344 3.952 8.344 3.687C8.344 3.343 8.521 3.023 8.812 2.84C9.415 2.462 9.923 2.048 10.328 1.655C10.769 1.228 11.382 1 12 1C12.618 1 13.231 1.228 13.672 1.655C14.749 2.7 16.55 3.892 18.935 4.175C20.094 4.313 21 5.255 21 6.383V12.571C21 13.173 20.969 13.778 20.889 14.373C20.823 14.87 20.399 15.241 19.898 15.241C19.633 15.241 19.378 15.136 19.191 14.948L8.637 4.394Z");
  stroke: none;
}

</style>
