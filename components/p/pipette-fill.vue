<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wogq9sm4o"/><path class="tf-f2cj0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pipette-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tf-f2cj0g {
  d: path("M4.1314 19.8686L3 21");
}

.wogq9sm4o {
  fill: currentColor;
  d: path("M14.1134 15.3313L8.6687 9.8866C7.419 8.6369 7.419 6.6107 8.6687 5.3611C9.9184 4.1114 11.9445 4.1114 13.1942 5.3611L13.2649 5.4318L15.5984 3.0983C17.0629 1.6338 19.4372 1.6338 20.9017 3.0983C22.3662 4.5628 22.3662 6.9371 20.9017 8.4016L18.5682 10.7351L18.6389 10.8058C19.8886 12.0555 19.8886 14.0816 18.6389 15.3313C17.3893 16.581 15.3631 16.581 14.1134 15.3313ZM7.007 12.4675L3.8485 15.626C3.5693 15.9052 3.379 16.2608 3.3016 16.648L2.8773 18.7693C2.7461 19.425 2.9514 20.1029 3.4243 20.5757C3.8971 21.0486 4.575 21.2539 5.2307 21.1227L7.352 20.6984C7.7392 20.621 8.0948 20.4307 8.374 20.1515L11.5325 16.993C11.923 16.6024 11.923 15.9693 11.5325 15.5788L8.4212 12.4675C8.0307 12.077 7.3976 12.077 7.007 12.4675Z");
  stroke: none;
}

</style>
