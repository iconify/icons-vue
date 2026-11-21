<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vbty78bap"/><path class="gjrtwdihh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pipette-sharp-fill" /></template>
<style>
.gjrtwdihh {
  d: path("M4.1314 19.8686L2.7071 21.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vbty78bap {
  fill: currentColor;
  d: path("M14.1134 15.3313L8.6687 9.8866C7.419 8.6369 7.419 6.6107 8.6687 5.3611C9.9184 4.1114 11.9445 4.1114 13.1942 5.3611L13.2649 5.4318L15.5984 3.0983C17.0629 1.6338 19.4372 1.6338 20.9017 3.0983C22.3662 4.5628 22.3662 6.9371 20.9017 8.4016L18.5682 10.7351L18.6389 10.8058C19.8886 12.0555 19.8886 14.0816 18.6389 15.3313C17.3893 16.581 15.3631 16.581 14.1134 15.3313ZM7.007 12.4675L4.2021 15.2724C4.0625 15.412 3.9673 15.5898 3.9286 15.7834L3.1507 19.6725C3.0852 20.0004 3.1878 20.3393 3.4243 20.5757C3.6607 20.8122 3.9996 20.9148 4.3275 20.8493L8.2166 20.0714C8.4102 20.0327 8.588 19.9375 8.7276 19.7979L11.5325 16.993C11.923 16.6024 11.923 15.9693 11.5325 15.5788L8.4212 12.4675C8.0307 12.077 7.3976 12.077 7.007 12.4675Z");
  stroke: none;
}

</style>
