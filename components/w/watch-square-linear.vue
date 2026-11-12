<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g9v60on3f"/><path class="e1_dsdb2x"/><path class="fdsu-dbih"/><path class="e8n1d8bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:watch-square-linear" /></template>
<style>
.e1_dsdb2x {
  stroke-linejoin: round;
  d: path("M12 8.99998V12.0769L14 14");
}

.e8n1d8bgz {
  d: path("M7.23828 18.5763L7.30304 18.8677C7.63674 20.3694 7.80359 21.1202 8.35199 21.5601C8.9004 22 9.66953 22 11.2078 22H12.7904C14.3287 22 15.0978 22 15.6462 21.5601C16.1946 21.1202 16.3615 20.3694 16.6952 18.8677L16.7599 18.5763");
}

.fdsu-dbih {
  d: path("M7.23828 5.42371L7.30304 5.13228C7.63674 3.63065 7.80359 2.87983 8.35199 2.43992C8.9004 2 9.66953 2 11.2078 2H12.7904C14.3287 2 15.0978 2 15.6462 2.43992C16.1946 2.87983 16.3615 3.63065 16.6952 5.13228L16.7599 5.42366");
}

.g9v60on3f {
  d: path("M12 19C9.19108 19 7.78661 19 6.77772 18.3259C6.34096 18.034 5.96596 17.659 5.67412 17.2223C5 16.2134 5 14.8089 5 12C5 9.19108 5 7.78661 5.67412 6.77772C5.96596 6.34096 6.34096 5.96596 6.77772 5.67412C7.78661 5 9.19108 5 12 5C14.8089 5 16.2134 5 17.2223 5.67412C17.659 5.96596 18.034 6.34096 18.3259 6.77772C19 7.78661 19 9.19108 19 12C19 14.8089 19 16.2134 18.3259 17.2223C18.034 17.659 17.659 18.034 17.2223 18.3259C16.2134 19 14.8089 19 12 19Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
