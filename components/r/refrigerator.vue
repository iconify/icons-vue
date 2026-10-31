<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er55_tbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refrigerator" /></template>
<style>
.er55_tbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 2L16 2C17.6569 2 19 3.3431 19 5L19 19C19 20.6569 17.6569 22 16 22L8 22C6.3431 22 5 20.6569 5 19L5 5C5 3.3431 6.3431 2 8 2ZM5 11L19 11M9 6L9 7M9 15L9 18");
}

</style>
