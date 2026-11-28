<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="daidzgjcj"/><path class="tl5balbkf"/><path clip-rule="evenodd" class="t4apaeiyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-duotone" /></template>
<style>
.daidzgjcj {
  stroke-opacity: 0.4;
  d: path("M3 8V6C3 4.343 4.3432 3 6 3H8M16 3H18C19.6569 3 21 4.343 21 6V8M21 16V18C21 19.657 19.6569 21 18 21H16M8 21H6C4.3432 21 3 19.657 3 18V16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t4apaeiyt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 10.034C6.001 9.283 6.423 8.595 7.0925 8.255L11.0925 6.218C11.6627 5.927 12.3374 5.927 12.9076 6.218L16.9076 8.255C17.5772 8.596 17.999 9.283 18 10.034L12.4579 12.889C12.3163 12.962 12.1593 13 12 13C11.8407 13 11.6837 12.962 11.5421 12.889L6 10.034Z");
  stroke: none;
}

.tl5balbkf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.9076 16.764L12.9076 17.782C12.3374 18.073 11.6627 18.073 11.0925 17.782L7.0925 15.745C6.4223 15.404 6 14.716 6 13.963V10.037C6 9.284 6.4222 8.596 7.0925 8.255L11.0925 6.218C11.6627 5.927 12.3374 5.927 12.9076 6.218L16.9076 8.255C17.578 8.596 18 9.285 18 10.037V13.963C18 14.715 17.578 15.404 16.9076 15.745L14.9076 16.764Z");
  stroke: none;
}

</style>
