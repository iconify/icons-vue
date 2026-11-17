<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz_2tv_ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-arrow-right-sharp" /></template>
<style>
.uz_2tv_ks {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5H10.5C8.567 5 7 6.567 7 8.5C7 10.433 8.567 12 10.5 12H14.5C16.433 12 18 13.567 18 15.5C18 17.433 16.433 19 14.5 19H9M9 19C9 17.343 7.657 16 6 16C4.343 16 3 17.343 3 19C3 20.657 4.343 22 6 22C7.657 22 9 20.657 9 19ZM15 2V8L21 5L15 2Z");
}

</style>
