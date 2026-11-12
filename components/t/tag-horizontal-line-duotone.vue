<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gr36f96bd"/><path class="zit9rtjxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-horizontal-line-duotone" /></template>
<style>
.gr36f96bd {
  d: path("M13.358 21H10.721C6.8456 21 4.90789 21 3.70394 19.7552C2.5 18.5104 2.5 16.5069 2.5 12.5C2.5 8.49306 2.5 6.48959 3.70394 5.2448C4.90789 4 6.84561 4 10.721 4H13.358C15.5854 4 16.6992 4 17.6289 4.53277C18.5586 5.06554 19.1488 6.04203 20.3294 7.99501L21.0102 9.12126C22.0034 10.7643 22.5 11.5858 22.5 12.5C22.5 13.4142 22.0034 14.2357 21.0102 15.8787L20.3294 17.005C19.1488 18.958 18.5586 19.9345 17.6289 20.4672C16.6992 21 15.5854 21 13.358 21Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zit9rtjxt {
  d: path("M7.5 7.99512V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
