<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o09_85b2p"/><path class="talqocv5s"/><path class="g6m7dacnz"/><path class="ialw77bui"/><circle class="wmc73-bhg"/><path class="l8832db4d"/><path class="zvb1o0zip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:toilet" /></template>
<style>
.g6m7dacnz {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M18 16H6a2 2 0 0 0-2 2h16a2 2 0 0 0-2-2m2-16v18c1.104 0 2-1.007 2-2.25V2.25C22 1.007 21.104 0 20 0");
}

.ialw77bui {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M34 4a2 2 0 0 0-2-2h-8a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2z");
}

.l8832db4d {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M22 4h12v2H22z");
}

.o09_85b2p {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M26 18v2H13.293c-.867 0-1.835.896-2.161 2L7.59 34c-.326 1.104.306 2 1.41 2h18a2 2 0 0 0 2-2V24a3.99 3.99 0 0 1 3-3.858V18z");
}

.talqocv5s {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M22 21.875C22 25.396 17.522 29 12 29S2 25.396 2 21.875C2 20 2.833 20 12 20s10 0 10 1.875M25 19c0 .553-.514 1-1.15 1H3.15C2.515 20 2 19.553 2 19s.515-1 1.15-1h20.7c.636 0 1.15.447 1.15 1");
}

.wmc73-bhg {
  cx: 20px;
  cy: 16px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.zvb1o0zip {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M25 21a1 1 0 0 1-1 1H3a1 1 0 1 1 0-2h21a1 1 0 0 1 1 1");
}

</style>
