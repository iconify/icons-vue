<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zykeq5bdg"/><path class="it12y4b4a"/><path class="l6md27rub"/><path class="nwrm-pbrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it12y4b4a {
  stroke-linejoin: round;
  d: path("M22 18V15.6429C22 13.6479 22 12.6505 21.7194 11.8486C21.2169 10.4124 20.0876 9.28314 18.6514 8.78058C17.8495 8.5 16.8521 8.5 14.8571 8.5C14.0592 8.5 13.6602 8.5 13.3394 8.61223C12.7649 8.81326 12.3133 9.26495 12.1122 9.83944C12 10.1602 12 10.5592 12 11.3571V16");
}

.l6md27rub {
  stroke-linejoin: round;
  d: path("M2 16H22");
}

.nwrm-pbrz {
  d: path("M9.5 11C9.5 12.3807 8.38071 13.5 7 13.5C5.61929 13.5 4.5 12.3807 4.5 11C4.5 9.61929 5.61929 8.5 7 8.5C8.38071 8.5 9.5 9.61929 9.5 11Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zykeq5bdg {
  stroke-linejoin: round;
  d: path("M2 6V18");
}

</style>
