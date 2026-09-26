<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abfeulbnv"/><path clip-rule="evenodd" class="heu85pu5d"/><path class="g2zfn4rww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-basket-plus-duotone" /></template>
<style>
.abfeulbnv {
  stroke-opacity: 0.4;
  d: path("M9 10L9.8773 3.8586C9.9477 3.3659 10.3696 3 10.8673 3L14.847 3C15.4555 3 15.923 3.539 15.8369 4.1414L15 10");
}

.g2zfn4rww {
  d: path("M19 15V21M16 18H22");
}

.heu85pu5d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 22L6.4817 22C5.1614 22 3.9963 21.1369 3.6118 19.8739L1.087 11.5826C1.0295 11.3937 1.0003 11.1974 1.0003 11C1.0003 9.8954 1.8957 9 3.0003 9L20.9997 9C22.1043 9 22.9997 9.8954 22.9997 11C22.9997 11.5523 22.5526 12 22.0004 12L16 12C14.3431 12 13 13.3431 13 15L13 21C13 21.5523 12.5523 22 12 22Z");
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
