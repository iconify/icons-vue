<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x5ls4k8te"/><path class="yfgshbc-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-minus-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x5ls4k8te {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 10C1 8.895431 1.895431 8 3 8L5.477658 8L8.3585 3.861189C9.477163 2.254043 12 3.045621 12 5.003765L12 18.996235C12 20.954379 9.477163 21.745957 8.3585 20.138811L5.477658 16L3 16C1.895431 16 1 15.104569 1 14Z");
  stroke: none;
}

.yfgshbc-l {
  d: path("M2 10C2 9.447715 2.447715 9 3 9L5.477658 9C5.804909 9 6.111453 8.839879 6.298408 8.571288L9.17925 4.432477C9.738582 3.628903 11 4.024692 11 5.003764L11 18.996236C11 19.975308 9.738582 20.371097 9.17925 19.567523L6.298408 15.428712C6.111453 15.160121 5.804909 15 5.477658 15L3 15C2.447715 15 2 14.552285 2 14ZM16 12H22");
}

</style>
