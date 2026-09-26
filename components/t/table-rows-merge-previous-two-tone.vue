<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kkfqo28ih"/><path class="e6f20c6qj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-merge-previous-two-tone" /></template>
<style>
.e6f20c6qj {
  d: path("M6 21L18 21C19.6569 21 21 19.6569 21 18L21 6C21 4.3431 19.6569 3 18 3L6 3C4.3431 3 3 4.3431 3 6L3 18C3 19.6569 4.3431 21 6 21ZM3 17L21 17M3 8L5 8M21 8L19 8M12 13L12 7M9 10L12 7L15 10");
}

.kkfqo28ih {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 22L18 22C20.2091 22 22 20.2091 22 18L22 6C22 3.7909 20.2091 2 18 2L6 2C3.7909 2 2 3.7909 2 6L2 18C2 20.2091 3.7909 22 6 22ZM3 17L21 17L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 17Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
