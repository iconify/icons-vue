<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y-uxy98jv"/><path class="l2fu2bckx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-columns-split-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2fu2bckx {
  d: path("M2 15.333H5M5 15.333H10.9977M5 15.333L5 8.6665M5 15.333L5 21.9913M10.9977 15.333H11M10.9977 15.333C11 14.9168 11 14.4733 11 14L11 10C11 9.52656 11 9.08283 10.9977 8.6665M2 22H3C3.73549 22 4.39926 22 5 21.9913C7.47957 21.9554 8.88534 21.7715 9.82843 20.8284C10.853 19.8039 10.9815 18.2332 10.9977 15.333M2 8.6665H5M5 8.6665H10.9977M5 8.6665L5 2.00873M10.9977 8.6665H11M10.9977 8.6665C10.9815 5.76657 10.8529 4.19607 9.82843 3.17157C8.65685 2 6.77124 2 3 2H2M21.9985 15.333H16.0067M16.0067 15.333H16.0043M16.0067 15.333C16.0044 14.9168 16.0044 14.4732 16.0044 14V9.99998C16.0044 9.52654 16.0044 9.08282 16.0067 8.6665M16.0067 15.333C16.0228 18.2332 16.1514 19.8039 17.176 20.8284C18.1183 21.7708 19.5227 21.9551 21.9987 21.9912M21.9961 8.6665H16.0067M16.0067 8.6665H16.0043M16.0067 8.6665C16.0229 5.76656 16.1515 4.19604 17.176 3.17155C18.1175 2.23006 19.5201 2.04516 21.9918 2.00885");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y-uxy98jv {
  d: path("M13.5 2.00879V3.67267M13.5 20.3502V22.014M13.5 7.00269V10.3488M13.5 13.66V17.0062");
}

</style>
