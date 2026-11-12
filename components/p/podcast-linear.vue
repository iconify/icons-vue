<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vesdrnt2r"/><path class="lh43htbqq"/><path class="unm252b3m"/><path class="cob7fzbqj"/><path class="apggyjblr"/><path class="nb3kikr6t"/><path class="kdi5mwb3a"/><path class="n30k0z4xd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-linear" /></template>
<style>
.apggyjblr {
  d: path("M4.1543 16C5.1739 16 6.00045 15.1734 6.00045 14.1538V9.99998C6.00045 6.68628 8.68673 4 12.0004 4C15.3141 4 18.0004 6.68628 18.0004 9.99998V14.1538C18.0004 15.1734 18.827 16 19.8466 16");
}

.cob7fzbqj {
  d: path("M9 10H10M9 13L10 13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdi5mwb3a {
  d: path("M20 16C18.8954 16 18 15.1046 18 14V12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12V14C22 15.1046 21.1046 16 20 16Z");
}

.lh43htbqq {
  d: path("M13 10L15 10");
}

.n30k0z4xd {
  d: path("M12 16V19");
}

.nb3kikr6t {
  d: path("M4 16C2.89543 16 2 15.1046 2 14V12C2 10.8954 2.89543 10 4 10C5.10457 10 6 10.8954 6 12V14C6 15.1046 5.10457 16 4 16Z");
}

.unm252b3m {
  d: path("M13 13L15 13");
}

.vesdrnt2r {
  d: path("M12 16C10.3431 16 9 14.6569 9 13V10C9 8.34315 10.3431 7 12 7C13.6569 7 15 8.34315 15 10V13C15 14.6569 13.6569 16 12 16Z");
}

</style>
