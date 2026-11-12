<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hqpl1bcby"/><path class="k9htqua9u"/><path class="p1tpmgbyh"/><path class="h6_ngrzeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-3-line-duotone" /></template>
<style>
.h6_ngrzeb {
  d: path("M14 14C14 14 14.2813 15.4596 15.911 17.0892C17.5407 18.7189 19 19 19 19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hqpl1bcby {
  d: path("M11 9.5C11 8.34835 10.5607 7.1967 9.68198 6.31802C7.92462 4.56066 5.07538 4.56066 3.31802 6.31802C2.43934 7.1967 2 8.34835 2 9.5M11 9.5C11 10.6517 10.5607 11.8033 9.68198 12.682C7.92462 14.4393 5.07538 14.4393 3.31802 12.682C2.43934 11.8033 2 10.6517 2 9.5M11 9.5H2");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9htqua9u {
  d: path("M19.0002 2.87892C17.8287 1.70735 15.9292 1.70735 14.7576 2.87892C14.1718 3.46471 13.8789 4.23248 13.8789 5.00024C13.8789 5.76801 14.1718 6.53578 14.7576 7.12156C15.9292 8.29314 17.8287 8.29314 19.0002 7.12156C19.586 6.53578 19.8789 5.76801 19.8789 5.00024C19.8789 4.23248 19.586 3.46471 19.0002 2.87892Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.p1tpmgbyh {
  d: path("M20.9052 17.381C22.3649 15.9213 22.3649 13.5546 20.9052 12.0948C19.4454 10.6351 17.0787 10.6351 15.619 12.0948L12.0948 15.619C10.6351 17.0787 10.6351 19.4454 12.0948 20.9052C13.5546 22.3649 15.9213 22.3649 17.381 20.9052L20.9052 17.381Z");
}

</style>
