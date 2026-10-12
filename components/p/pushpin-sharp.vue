<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o111iwugk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pushpin-sharp" /></template>
<style>
.o111iwugk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.09 7.49l1.42 1.42l.53.53l-.53.53l-2.12 2.12l-.53.53v4.59l-.53-.53l-6.01-6.01l-.53-.53h4.59l.53-.53l2.12-2.12l.53-.53zm.08-3.26l4.6 4.6m-9.45 4.85l-6.01 6.01");
}

</style>
