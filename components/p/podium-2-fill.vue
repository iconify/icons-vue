<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hcwu-jb1u"/><path class="bvzj4mazs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-2-fill" /></template>
<style>
.bvzj4mazs {
  d: path("M2 22H22M4 22V18.5H9V15H14V11.5H20V22H4ZM15.3 3.4C15.3 2.3 16.116 2 17 2C17.884 2 18.7 2.5 18.7 3.5C18.7 4.9 15.3 6.3 15.3 7H18.7");
}

.hcwu-jb1u {
  fill: currentColor;
  d: path("M4 22V18.5H9V15H14V11.5H20V22H4Z");
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
