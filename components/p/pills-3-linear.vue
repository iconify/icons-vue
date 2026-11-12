<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hqpl1bcby"/><path class="yc8xgkbyw"/><path class="ed-q8abvo"/><path class="hqsaabc6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-3-linear" /></template>
<style>
.ed-q8abvo {
  d: path("M12.0948 20.9052C13.5546 22.3649 15.9213 22.3649 17.381 20.9052L20.9052 17.381C22.3649 15.9213 22.3649 13.5546 20.9052 12.0948C19.4454 10.6351 17.0787 10.6351 15.619 12.0948L12.0948 15.619C10.6351 17.0787 10.6351 19.4454 12.0948 20.9052Z");
}

.hqpl1bcby {
  d: path("M11 9.5C11 8.34835 10.5607 7.1967 9.68198 6.31802C7.92462 4.56066 5.07538 4.56066 3.31802 6.31802C2.43934 7.1967 2 8.34835 2 9.5M11 9.5C11 10.6517 10.5607 11.8033 9.68198 12.682C7.92462 14.4393 5.07538 14.4393 3.31802 12.682C2.43934 11.8033 2 10.6517 2 9.5M11 9.5H2");
}

.hqsaabc6g {
  d: path("M14 14C14 14 14.2813 15.4596 15.911 17.0892C17.5407 18.7189 19 19 19 19");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc8xgkbyw {
  d: path("M19 7.12156C17.8284 8.29314 15.9289 8.29314 14.7574 7.12156C14.1716 6.53578 13.8787 5.76801 13.8787 5.00024C13.8787 4.23248 14.1716 3.46471 14.7574 2.87892C15.9289 1.70735 17.8284 1.70735 19 2.87892C19.5858 3.46471 19.8787 4.23248 19.8787 5.00024C19.8787 5.76801 19.5858 6.53578 19 7.12156Z");
}

</style>
