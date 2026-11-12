<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="plbs7_b_u"/><path class="fyp478bsy"/><path class="r7-rdsqaq"/><path class="il_gdve3e"/><path class="hw-5-kgoz"/><path class="utiw4jbqs"/><path class="nhunzz9zc"/><path class="zlsyrsb8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-replace-line-duotone" /></template>
<style>
.fyp478bsy {
  d: path("M14 22H17C18.8856 22 19.8284 22 20.4142 21.4142C21 20.8284 21 19.8856 21 18C21 16.1144 21 15.1716 20.4142 14.5858C19.8284 14 18.8856 14 17 14H14C12.1144 14 11.1716 14 10.5858 14.5858C10 15.1716 10 16.1144 10 18C10 19.8856 10 20.8284 10.5858 21.4142C11.1716 22 12.1144 22 14 22Z");
}

.hw-5-kgoz {
  stroke-linejoin: round;
  d: path("M22 10L21 11L20 10");
}

.il_gdve3e {
  d: path("M13.5 14.5V18M13.5 18V22M13.5 18H11M17.5 14.5V18M17.5 18V22M17.5 18H21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhunzz9zc {
  stroke-linejoin: round;
  d: path("M2 14L3 13L4 14");
}

.plbs7_b_u {
  d: path("M6 10H11C12.8856 10 13.8284 10 14.4142 9.41421C15 8.82843 15 7.88562 15 6C15 4.11438 15 3.17157 14.4142 2.58579C13.8284 2 12.8856 2 11 2H6C4.11438 2 3.17157 2 2.58579 2.58579C2 3.17157 2 4.11438 2 6C2 7.88562 2 8.82843 2.58579 9.41421C3.17157 10 4.11438 10 6 10Z");
}

.r7-rdsqaq {
  d: path("M6 2.5V6M6 6V10M6 6H2.5M11 2.5V6M11 6V10M11 6H15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.utiw4jbqs {
  stroke-linejoin: round;
  d: path("M21 11V10C21 9.06812 21 7.60218 20.8478 7.23463C20.6448 6.74458 20.2554 6.35523 19.7654 6.15224C19.3978 6 18.9319 6 18 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zlsyrsb8p {
  stroke-linejoin: round;
  d: path("M3 13V14C3 14.9319 3 16.3978 3.15224 16.7654C3.35523 17.2554 3.74458 17.6448 4.23463 17.8478C4.60218 18 5.06812 18 6 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
