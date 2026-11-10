<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_42pqosn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-inward-horizontal-sharp" /></template>
<style>
.r_42pqosn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M23 12H1M12 8.26L7.777 2H16.223L12 8.26ZM12 15.74L7.777 22H16.223L12 15.74Z");
}

</style>
