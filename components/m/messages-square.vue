<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uapph2b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-square" /></template>
<style>
.uapph2b4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 10L19 10C20.1046 10 21 10.8954 21 12L21 21L18 18L14 18C12.8954 18 12 17.1046 12 16L12 12C12 10.8954 12.8954 10 14 10ZM6 13L3 16L3 5C3 3.8954 3.8954 3 5 3L14 3C15.1046 3 16 3.8954 16 5L16 6");
}

</style>
