<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lj5jgub7q"/><path class="soqa3hs6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-arrow-left-duotone" /></template>
<style>
.lj5jgub7q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 13L10 13C13.866 13 17 16.134 17 20C17 21.1046 16.1046 22 15 22L3 22C1.8954 22 1 21.1046 1 20C1 16.134 4.134 13 8 13ZM13 7C13 9.2091 11.2091 11 9 11C6.7909 11 5 9.2091 5 7C5 4.7909 6.7909 3 9 3C11.2091 3 13 4.7909 13 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.soqa3hs6a {
  d: path("M22 7H16M19 4L16 7L19 10");
}

</style>
