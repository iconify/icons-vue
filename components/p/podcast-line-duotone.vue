<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vesdrnt2r"/><path class="gneiz5g1r"/><path class="idkcu5_5f"/><path class="edd_8bc6q"/><path class="h068npaan"/><path class="s2q92fbgb"/><path class="nb3kikr6t"/><path class="kdi5mwb3a"/><path class="j17hywdzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-line-duotone" /></template>
<style>
.edd_8bc6q {
  d: path("M9 10L10 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gneiz5g1r {
  d: path("M13 10L15 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.h068npaan {
  d: path("M9 13L10 13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.idkcu5_5f {
  d: path("M13 13L15 13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j17hywdzm {
  d: path("M12 16V19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kdi5mwb3a {
  d: path("M20 16C18.8954 16 18 15.1046 18 14V12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12V14C22 15.1046 21.1046 16 20 16Z");
}

.nb3kikr6t {
  d: path("M4 16C2.89543 16 2 15.1046 2 14V12C2 10.8954 2.89543 10 4 10C5.10457 10 6 10.8954 6 12V14C6 15.1046 5.10457 16 4 16Z");
}

.s2q92fbgb {
  d: path("M4.1543 16C5.1739 16 6.00045 15.1734 6.00045 14.1538V9.99998C6.00045 6.68628 8.68673 4 12.0004 4C15.3141 4 18.0004 6.68628 18.0004 9.99998V14.1538C18.0004 15.1734 18.827 16 19.8466 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vesdrnt2r {
  d: path("M12 16C10.3431 16 9 14.6569 9 13V10C9 8.34315 10.3431 7 12 7C13.6569 7 15 8.34315 15 10V13C15 14.6569 13.6569 16 12 16Z");
}

</style>
