<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ly1xdlesy"/><path clip-rule="evenodd" class="fcl1l5b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-line-summary-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fcl1l5b3h {
  fill-rule: evenodd;
  d: path("M21 7C21.5523 7 22 7.45 22 8C22 8.55 21.5523 9 21 9H7C6.4477 9 6 8.55 6 8C6 7.45 6.4477 7 7 7H21ZM21 2C21.5523 2 22 2.45 22 3C22 3.55 21.5523 4 21 4H7C6.4477 4 6 3.55 6 3C6 2.45 6.4477 2 7 2H21ZM14 12C14.5523 12 15 12.45 15 13C15 13.55 14.5523 14 14 14H7C6.4477 14 6 13.55 6 13C6 12.45 6.4477 12 7 12H14Z");
}

.ly1xdlesy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2C3.5523 2 4 2.45 4 3V14.75C4 16.41 5.3432 17.75 7 17.75H18.4717L17.916 17.23C17.5133 16.85 17.4927 16.22 17.8701 15.82C18.2478 15.41 18.8813 15.39 19.2842 15.77L21.6836 18.02C21.8852 18.21 22 18.47 22 18.75C22 19.03 21.8852 19.29 21.6836 19.48L19.2842 21.73C18.8813 22.11 18.2478 22.09 17.8701 21.68C17.4927 21.28 17.5133 20.65 17.916 20.27L18.4717 19.75H7C4.2386 19.75 2 17.51 2 14.75V3C2 2.45 2.4477 2 3 2Z");
}

</style>
