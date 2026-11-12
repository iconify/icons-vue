<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lyac2jmak"/><path class="zavg8bcsl"/><path class="q56o60zyz"/><path class="q174hactj"/><path class="r2c3lfbwa"/><path class="il3m-sbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-2-linear" /></template>
<style>
.il3m-sbqt {
  d: path("M22 6.9585L20 6.9585");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyac2jmak {
  d: path("M9.5 14C11.1569 14 12.5 15.3431 12.5 17C12.5 18.6568 11.1569 20 9.5 20C7.84315 20 6.5 18.6568 6.5 17C6.5 15.3431 7.84315 14 9.5 14Z");
}

.q174hactj {
  d: path("M9 6.9585L2 6.9585");
}

.q56o60zyz {
  d: path("M15 16.9585L22 16.9585");
}

.r2c3lfbwa {
  d: path("M2 16.9585L4 16.9585");
}

.zavg8bcsl {
  d: path("M14.5 3.99998C12.8431 3.99998 11.5 5.34312 11.5 6.99998C11.5 8.65683 12.8431 9.99998 14.5 9.99998C16.1569 9.99998 17.5 8.65683 17.5 6.99998C17.5 5.34312 16.1569 3.99998 14.5 3.99998Z");
}

</style>
