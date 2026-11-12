<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b_l8t2bil"/><path class="lxnaexxsa"/><path class="pqr2gub2q"/><path class="r7m1as5xz"/><path class="mx9f_4bzg"/><path class="ht1jk4zsa"/><path class="r762e5d0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-2-line-duotone" /></template>
<style>
.b_l8t2bil {
  d: path("M8.5 4H8C5.17157 4 3.75736 4 2.87868 4.87868C2 5.75736 2 7.17157 2 10V14C2 16.8284 2 18.2426 2.87868 19.1213C3.75736 20 5.17157 20 8 20H8.5M15.5 4H16C18.8284 4 20.2426 4 21.1213 4.87868C22 5.75736 22 7.17157 22 10V14C22 16.8284 22 18.2426 21.1213 19.1213C20.2426 20 18.8284 20 16 20H15.5");
}

.ht1jk4zsa {
  d: path("M12 7.5V8.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxnaexxsa {
  d: path("M17 4V9M17 9V15M17 9H21.5M17 15V20M17 15H21.5M7 4V9M7 9V15M7 9H2.5M7 15V20M7 15H2.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mx9f_4bzg {
  d: path("M12 11.5V12.5");
}

.pqr2gub2q {
  d: path("M10.8621 2H13.1389C13.5228 2 13.7635 2.41474 13.573 2.74807L12.4346 4.74029C12.2427 5.07619 11.7583 5.07619 11.5664 4.74029L10.4279 2.74807C10.2375 2.41474 10.4782 2 10.8621 2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r762e5d0s {
  d: path("M12 15.5V16.5");
}

.r7m1as5xz {
  d: path("M10.8621 22H13.1389C13.5228 22 13.7635 21.5853 13.573 21.252L12.4346 19.2597C12.2427 18.9238 11.7583 18.9238 11.5664 19.2597L10.4279 21.252C10.2375 21.5853 10.4782 22 10.8621 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
