<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="srug0hb7t"/><path class="mcgaswbyw"/><path class="vnda1s8vz"/><path class="xv6kuw8hw"/><path class="oxdhi_ktu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-vacuum-cleaner-linear" /></template>
<style>
.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcgaswbyw {
  d: path("M16.6451 20.858C17.1555 21.2601 17.7998 21.5001 18.5 21.5001C20.1569 21.5001 21.5 20.1569 21.5 18.5001C21.5 17.7998 21.2601 17.1556 20.858 16.6451");
}

.oxdhi_ktu {
  d: path("M22 12C22 13.6768 21.5873 15.2571 20.858 16.6451C19.9144 18.4408 18.4408 19.9144 16.6451 20.858C15.2571 21.5873 13.6768 22 12 22C10.3231 22 8.74265 21.5873 7.35462 20.8578C5.55894 19.9142 4.08536 18.4405 3.14183 16.6447C2.41261 15.2568 2 13.6766 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.srug0hb7t {
  d: path("M15 9C15 10.6569 13.6569 12 12 12C10.3431 12 9 10.6569 9 9C9 7.34315 10.3431 6 12 6C13.6569 6 15 7.34315 15 9Z");
}

.vnda1s8vz {
  d: path("M7.35462 20.8579C6.84413 21.2601 6.19984 21.5001 5.49951 21.5001C3.84266 21.5001 2.49951 20.1569 2.49951 18.5001C2.49951 17.7996 2.73954 17.1553 3.14183 16.6448");
}

.xv6kuw8hw {
  d: path("M12 18V16");
}

</style>
