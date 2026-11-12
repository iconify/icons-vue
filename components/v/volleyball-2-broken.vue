<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y2kstw56z"/><path class="mbcrec3yn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volleyball-2-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbcrec3yn {
  d: path("M3.3385 6.99829C4.18688 5.526 5.42231 4.25042 6.99972 3.33971C11.7826 0.578283 17.8985 2.21703 20.66 6.99996C23.4214 11.7829 21.7826 17.8988 16.9997 20.6602C12.2168 23.4216 6.10089 21.7829 3.33946 17C2.42874 15.4226 1.99663 13.7002 1.99805 12.0009");
}

.y2kstw56z {
  stroke-linejoin: round;
  d: path("M12 2L11.3142 3.64586C10.1761 6.37726 10.4317 9.49075 12 12M12 12H12.0917C15.4705 12 18.6258 13.6887 20.5 16.5M12 12L11.5697 12.5532C9.63285 15.0435 6.65478 16.5 3.5 16.5M21.9877 11.5L21.2426 10.7426C19.2445 8.74454 16.7228 7.39047 14 6.81401M5.7327 19.7928C8.99597 19.7928 12.2916 18.6283 15 16.7104M7.5 3.06729C6.30741 5.92951 6.00374 9.02101 6.58899 12");
}

</style>
