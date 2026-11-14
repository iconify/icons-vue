<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kr6grkbdu"/><path class="t8sozokui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:title-insurance" /></template>
<style>
.kr6grkbdu {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.5-7.5 10.5c-4-2-7.5-5.5-7.5-10.5V5.5Z");
}

.t8sozokui {
  d: path("M8 7h8v2.25H8Zm1 2.25V14m6-4.75V14m-7 0h8v2.25H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
