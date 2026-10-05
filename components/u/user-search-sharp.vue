<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9nwlmbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-search-sharp" /></template>
<style>
.y9nwlmbty {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3432 10 6 8.6569 6 7C6 5.3431 7.3432 4 9 4ZM11 21L2 21L2 20C2 16.6863 4.6863 14 8 14L10 14C10.2868 14 10.5733 14.0206 10.8571 14.0615M21 17C21 18.6569 19.6569 20 18 20C16.3431 20 15 18.6569 15 17C15 15.3431 16.3431 14 18 14C19.6569 14 21 15.3431 21 17ZM20.1213 19.1213L20.5 19.5L22 21L22.2929 21.2929");
}

</style>
