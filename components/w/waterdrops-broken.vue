<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z_nmibcey"/><path class="smbap4brt"/><path class="uzlpqcb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:waterdrops-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.smbap4brt {
  d: path("M22 17.8333C22 20.1345 20.2091 22 18 22C15.7909 22 14 20.1345 14 17.8333C14 16.3935 15.5659 14.4718 16.7382 13.2349C17.4322 12.5026 18.5678 12.5026 19.2618 13.2349C20.4341 14.4718 22 16.3935 22 17.8333Z");
}

.uzlpqcb4o {
  d: path("M13.2618 3.23485C12.5678 2.50261 11.4322 2.50261 10.7382 3.23485C9.56593 4.47177 8 6.39349 8 7.83331C8 10.1345 9.79086 12 12 12C14.2091 12 16 10.1345 16 7.83331C16 7.56938 15.9474 7.28925 15.8542 7.00012");
}

.z_nmibcey {
  d: path("M10 17.8333C10 20.1345 8.20914 22 6 22C3.79086 22 2 20.1345 2 17.8333C2 16.3935 3.56593 14.4718 4.73823 13.2349C5.43222 12.5026 6.56778 12.5026 7.26177 13.2349C8.43407 14.4718 10 16.3935 10 17.8333Z");
}

</style>
