<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sdbjlwl-u"/><path class="fg9e45exk"/><path class="te0_fmbtj"/><path class="sbmsxlkla"/><path class="cgj19skhd"/><path class="ec3904xcj"/><path class="qj50m-btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:perfume-broken" /></template>
<style>
.cgj19skhd {
  d: path("M2.5 13C3.93501 13.5805 5.64292 14.7308 7.86069 14.9805C10.3509 15.2609 11.8549 13.5843 14 13.2947");
}

.ec3904xcj {
  d: path("M20.5 5.24977C21.6958 5.94012 22.2174 7.27523 21.6651 8.23182C21.1128 9.1884 19.6958 9.40422 18.5 8.71387C17.3043 8.02351 16.7827 6.6884 17.335 5.73182C17.8872 4.77523 19.3043 4.55941 20.5 5.24977Z");
}

.fg9e45exk {
  stroke-linejoin: round;
  d: path("M13 7H7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qj50m-btt {
  d: path("M17.2594 5.87969L16.5557 5.52786C15.8615 5.18073 15.0959 5 14.3197 5H13.5");
}

.sbmsxlkla {
  d: path("M2.16133 16C2.05554 15.5138 2 15.0105 2 14.495C2 10.3556 5.58172 7 10 7C14.4183 7 18 10.3556 18 14.495C18 16.4098 17.2336 18.1569 15.9725 19.4817C15.5224 19.9546 15.2973 20.191 14.3538 20.5955C13.4102 21 12.7596 21 11.4584 21H8.5416C7.24039 21 6.58979 21 5.64624 20.5955C5.38106 20.4818 5.17262 20.3814 5 20.2853");
}

.sdbjlwl-u {
  stroke-linejoin: round;
  d: path("M13 5V5.42168V7H7V5.5V5C7 3.58579 7 2.87868 7.43934 2.43934C7.87868 2 8.58579 2 10 2C11.4142 2 12.1213 2 12.5607 2.43934C13 2.87868 13 3.58579 13 5Z");
}

.te0_fmbtj {
  d: path("M7.00865 4.00037C7.55695 3.99984 8 3.95063 8 4.50002C8 5.05231 7.55228 5.00023 7 5.00023");
}

</style>
