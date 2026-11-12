<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zykeq5bdg"/><path class="iyo-0bcus"/><path class="l6md27rub"/><path class="h0-cfhb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-broken" /></template>
<style>
.h0-cfhb6i {
  d: path("M7 13.5C5.61929 13.5 4.5 12.3807 4.5 11C4.5 9.61929 5.61929 8.5 7 8.5C8.38071 8.5 9.5 9.61929 9.5 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyo-0bcus {
  stroke-linejoin: round;
  d: path("M22 16V18M12 16V11.3571C12 10.5592 12 10.1602 12.1122 9.83944C12.3133 9.26495 12.7649 8.81326 13.3394 8.61223C13.6602 8.5 14.0592 8.5 14.8571 8.5C16.8521 8.5 17.8495 8.5 18.6514 8.78058C20.0876 9.28314 21.2169 10.4124 21.7194 11.8486");
}

.l6md27rub {
  stroke-linejoin: round;
  d: path("M2 16H22");
}

.zykeq5bdg {
  stroke-linejoin: round;
  d: path("M2 6V18");
}

</style>
