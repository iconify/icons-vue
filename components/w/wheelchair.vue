<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lgxgi6bvi"/><path clip-rule="evenodd" class="n--i37b8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wheelchair" /></template>
<style>
.lgxgi6bvi {
  d: path("M14.6944 19.73C13.639 20.55 12.3386 21 11 21C7.6863 21 5 18.31 5 15C5 13.22 5.7725 11.63 7 10.53M11 9V11M11 11V14C11 14.55 11.4477 15 12 15H15.8524C16.7061 15 17.4657 15.54 17.7435 16.35L19 20M11 11H15");
}

.n--i37b8y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 4C13 5.1 12.1046 6 11 6C9.8954 6 9 5.1 9 4C9 2.9 9.8954 2 11 2C12.1046 2 13 2.9 13 4Z");
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
