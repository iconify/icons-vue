<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z_nmibcey"/><path class="smbap4brt"/><path class="kcqls85-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:waterdrops-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcqls85-o {
  d: path("M16 7.83331C16 10.1345 14.2091 12 12 12C9.79086 12 8 10.1345 8 7.83331C8 6.39349 9.56593 4.47177 10.7382 3.23485C11.4322 2.50261 12.5678 2.50261 13.2618 3.23485C14.4341 4.47177 16 6.39349 16 7.83331Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.smbap4brt {
  d: path("M22 17.8333C22 20.1345 20.2091 22 18 22C15.7909 22 14 20.1345 14 17.8333C14 16.3935 15.5659 14.4718 16.7382 13.2349C17.4322 12.5026 18.5678 12.5026 19.2618 13.2349C20.4341 14.4718 22 16.3935 22 17.8333Z");
}

.z_nmibcey {
  d: path("M10 17.8333C10 20.1345 8.20914 22 6 22C3.79086 22 2 20.1345 2 17.8333C2 16.3935 3.56593 14.4718 4.73823 13.2349C5.43222 12.5026 6.56778 12.5026 7.26177 13.2349C8.43407 14.4718 10 16.3935 10 17.8333Z");
}

</style>
