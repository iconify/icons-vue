<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="v4hk4ebbn"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-off-fill" /></template>
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

.v4hk4ebbn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.8715 14.8715L20.8284 20.8284C20.0791 21.5797 19.0611 22.0014 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6C1.9986 4.9389 2.4203 3.9209 3.1716 3.1716L11.1285 11.1285C9.8642 11.5125 8.9998 12.6783 8.9998 13.9996C8.9998 15.6568 10.3432 17.0002 12.0004 17.0002C13.3217 17.0002 14.4875 16.1358 14.8715 14.8715ZM7.9497 3.7071C7.7621 3.5196 7.6567 3.2652 7.6567 2.9999C7.6567 2.4475 8.1045 1.9998 8.6569 2L16.1716 2C16.9672 2 17.7303 2.3161 18.2929 2.8787L21.1213 5.7071C21.6839 6.2697 22 7.0328 22 7.8284L22 15.3431C22.0002 15.8955 21.5525 16.3433 21.0001 16.3433C20.7348 16.3433 20.4804 16.2379 20.2929 16.0503L7.9497 3.7071Z");
  stroke: none;
}

</style>
