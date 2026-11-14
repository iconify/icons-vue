<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_ylqcc8a"/><path class="hpkjqk6-w"/><path class="ahmb8ab9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payroll-calendar" /></template>
<style>
.ahmb8ab9g {
  d: path("M19.25 16.75C19 16.25 18.5 16 18 16c-.75 0-1.25.5-1.25 1c0 1 2.5.5 2.5 2c0 .5-.5 1-1.25 1s-1-.25-1.25-.75");
}

.c_ylqcc8a {
  d: path("M12.4 21H3.5V4.5h17v7.7M8 2.5v4m8-4v4m-12.5 3h17");
}

.hpkjqk6-w {
  d: path("M7 12.5h4v4H7Zm7.5 5.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
