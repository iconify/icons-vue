<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z--qt0l-q"/><path class="o-tvj_5su"/><path class="y0cxd-7om"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-tvj_5su {
  stroke-linejoin: round;
  d: path("M7 21H17");
}

.y0cxd-7om {
  d: path("M4 12H20");
}

.z--qt0l-q {
  stroke-linejoin: round;
  d: path("M12 3H8C6.11438 3 5.17157 3 4.58579 3.58579C4 4.17157 4 5.11438 4 7V7.95M12 3H16C17.8856 3 18.8284 3 19.4142 3.58579C20 4.17157 20 5.11438 20 7V7.95M12 3V9M12 17V15M12 21V19.5");
}

</style>
