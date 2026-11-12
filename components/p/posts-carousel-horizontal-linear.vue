<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5l1hedvi"/><path class="i96tnwb9m"/><path class="n9n4_cako"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-horizontal-linear" /></template>
<style>
.i96tnwb9m {
  d: path("M22 19H21.5C20.1193 19 19 17.8807 19 16.5V7.5C19 6.11929 20.1193 5 21.5 5H22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5l1hedvi {
  d: path("M7.5 9L7.5 15C7.5 16.8856 7.5 17.8284 8.08579 18.4142C8.67157 19 9.61438 19 11.5 19H12.5C14.3856 19 15.3284 19 15.9142 18.4142C16.5 17.8284 16.5 16.8856 16.5 15V9C16.5 7.11438 16.5 6.17157 15.9142 5.58579C15.3284 5 14.3856 5 12.5 5L11.5 5C9.61438 5 8.67157 5 8.08579 5.58579C7.5 6.17157 7.5 7.11438 7.5 9Z");
}

.n9n4_cako {
  d: path("M2 19H2.5C3.88071 19 5 17.8807 5 16.5L5 7.5C5 6.11929 3.88071 5 2.5 5H2");
}

</style>
