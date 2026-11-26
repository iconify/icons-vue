<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="diqvbcccv"/><path class="h-tc6cbxa"/><path clip-rule="evenodd" class="j339ybc_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spline-fill" /></template>
<style>
.diqvbcccv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 13L5 13C6.1046 13 7 13.8954 7 15L7 17C7 18.1046 6.1046 19 5 19L3 19C1.8954 19 1 18.1046 1 17L1 15C1 13.8954 1.8954 13 3 13ZM20 5L21 5C22.1046 5 23 5.8954 23 7L23 9C23 10.1046 22.1046 11 21 11L19 11C17.8954 11 17 10.1046 17 9L17 7C17 5.8954 17.8954 5 19 5Z");
  stroke: none;
}

.h-tc6cbxa {
  d: path("M6 16C15 16 9 8 18 8");
}

.j339ybc_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 17C17.5 17.8285 16.8285 18.5 16 18.5C15.1715 18.5 14.5 17.8285 14.5 17C14.5 16.1715 15.1715 15.5 16 15.5C16.8285 15.5 17.5 16.1715 17.5 17ZM9.5 7C9.5 7.8285 8.8285 8.5 8 8.5C7.1715 8.5 6.5 7.8285 6.5 7C6.5 6.1715 7.1715 5.5 8 5.5C8.8285 5.5 9.5 6.1715 9.5 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
