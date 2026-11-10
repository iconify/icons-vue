<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj6y9i7fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-horizontal-sharp" /></template>
<style>
.zj6y9i7fh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 19C20 17.34 18.657 16 17 16H15C13.343 16 12 17.34 12 19M20 19C20 20.66 18.657 22 17 22H15C13.343 22 12 20.66 12 19M20 19H23M12 19H1M2 2V12H22V2H2Z");
}

</style>
