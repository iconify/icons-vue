<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w37s95bcr"/><path class="ncu9ifj7a"/><path class="jv-smqblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:three-squares-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jv-smqblp {
  d: path("M16 12H18C19.8856 12 20.8284 12 21.4142 11.4142C22 10.8284 22 9.88562 22 8V6C22 4.11438 22 3.17157 21.4142 2.58579C20.8284 2 19.8856 2 18 2H16C14.1144 2 13.1716 2 12.5858 2.58579C12 3.17157 12 4.11438 12 6V7V8C12 9.88562 12 10.8284 12.5858 11.4142C13.1716 12 14.1144 12 16 12Z");
}

.ncu9ifj7a {
  d: path("M12 7H11C9.11438 7 8.17157 7 7.58579 7.58579C7 8.17157 7 9.11438 7 11V12V13C7 14.8856 7 15.8284 7.58579 16.4142C8.17157 17 9.11438 17 11 17H13C14.8856 17 15.8284 17 16.4142 16.4142C17 15.8284 17 14.8856 17 13V12");
}

.w37s95bcr {
  d: path("M7 12H6C4.11438 12 3.17157 12 2.58579 12.5858C2 13.1716 2 14.1144 2 16V18C2 19.8856 2 20.8284 2.58579 21.4142C3.17157 22 4.11438 22 6 22H8C9.88562 22 10.8284 22 11.4142 21.4142C12 20.8284 12 19.8856 12 18V17");
}

</style>
