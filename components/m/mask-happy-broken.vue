<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ibwtqmhuq"/><path class="nxyeq8w_t"/><path class="r4ng58brp"/><path class="s6e9m8adu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-happy-broken" /></template>
<style>
.ibwtqmhuq {
  d: path("M21 7V6.71888C21 4.52896 21 3.434 20.2927 2.83487C19.5855 2.23574 18.5045 2.41591 16.3424 2.77626L15.288 2.95199C13.6477 3.22537 12.8276 3.36205 12 3.36205C11.1724 3.36205 10.3523 3.22537 8.71202 2.95199L7.6576 2.77626C5.49553 2.41591 4.4145 2.23574 3.70725 2.83487C3 3.434 3 4.52896 3 6.71888V12C3 17.4903 7.23896 20.1547 9.89856 21.286C10.62 21.5929 10.9807 21.7464 12 21.7464C13.0193 21.7464 13.38 21.5929 14.1014 21.286C16.761 20.1547 21 17.4903 21 12V11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxyeq8w_t {
  d: path("M6.5 9C6.79112 8.4174 7.57665 8 8.5 8C9.42335 8 10.2089 8.4174 10.5 9");
}

.r4ng58brp {
  d: path("M13.5 9C13.7911 8.4174 14.5766 8 15.5 8C16.4234 8 17.2089 8.4174 17.5 9");
}

.s6e9m8adu {
  d: path("M8.5 14C8.5 14 9.55 15 12 15C14.45 15 15.5 14 15.5 14");
}

</style>
