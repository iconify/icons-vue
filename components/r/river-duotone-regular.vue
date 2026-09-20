<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jo523lbcw"/><path class="lv_jsmtqq"/><path class="nq6698b_y"/><path class="he-6-nbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:river-duotone-regular" /></template>
<style>
.he-6-nbhf {
  d: path("M14 3v6l6 6v6");
}

.jo523lbcw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v6l6 6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lv_jsmtqq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 3v6l6 6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nq6698b_y {
  d: path("M4 3v6l6 6v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
