<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyb5mwb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-2-sharp" /></template>
<style>
.kyb5mwb1g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5H10.5C8.567 5 7 6.567 7 8.5C7 10.433 8.567 12 10.5 12H14.5C16.433 12 18 13.567 18 15.5C18 17.433 16.433 19 14.5 19H9M15 5C15 6.657 16.343 8 18 8C19.657 8 21 6.657 21 5C21 3.343 19.657 2 18 2C16.343 2 15 3.343 15 5ZM9 19C9 17.343 7.657 16 6 16C4.343 16 3 17.343 3 19C3 20.657 4.343 22 6 22C7.657 22 9 20.657 9 19Z");
}

</style>
