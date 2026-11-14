<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tlwzp58-a"/><path class="fk47l-sbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-brushing-kids" /></template>
<style>
.fk47l-sbi {
  d: path("M13 5.5L15.5 8l-3.25 3.25l-2.5-2.5Zm1.25 1.25l4.5-4.5m-1 11.75l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.tlwzp58-a {
  d: path("M10.963 3.599c-.83.203-1.497.651-2.463.651c-1.25 0-2-.75-3.25-.75C3.5 3.5 2.5 5 2.5 7c0 2.5.75 3.5 1.25 5.25L4.5 17c.25 1.25 1.75 1.25 2 0l.75-3.25h2.5l.119.516m.472 2.046L10.5 17c.164.818.862 1.101 1.396.848");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
