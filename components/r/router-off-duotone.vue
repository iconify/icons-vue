<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gl8usev9f"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.gl8usev9f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.7781 20.8981C20.53 20.9646 20.2691 21 20 21H4C2.3431 21 1 19.6569 1 18V14C1 12.3431 2.3431 11 4 11H5.7193L4.3632 5.5758C4.2822 5.2521 4.3691 4.9258 4.5687 4.6887L6.7476 6.8676L7.7807 11H10.88L20.7781 20.8981ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16ZM16.4172 12.1746C16.1823 11.9345 16.0739 11.5818 16.1613 11.232L18.0299 3.7575C18.1638 3.2217 18.7067 2.8959 19.2425 3.0299C19.7783 3.1638 20.1041 3.7067 19.9701 4.2425L18.2807 11H20C21.6569 11 23 12.3431 23 14V16.3431C23 16.8954 22.5523 17.3431 22 17.3431C21.7239 17.3431 21.4739 17.2312 21.2929 17.0502L16.9498 12.7071C16.8604 12.6178 16.7879 12.5116 16.7374 12.3937C16.6148 12.3413 16.5068 12.2662 16.4172 12.1746Z");
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
