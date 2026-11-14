<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a9b3ocpqx"/><path class="o-2mqjl7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payroll-audit" /></template>
<style>
.a9b3ocpqx {
  d: path("M2.5 8.5h6v13h-6Zm8.75.5a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm8.25 3.5l2 2m-19-2.75h6M2.5 15h6m-6 3.25h6");
}

.o-2mqjl7p {
  d: path("M14.25 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
