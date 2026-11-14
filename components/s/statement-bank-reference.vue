<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gtqc9hhus"/><path class="k41-wijft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-bank-reference" /></template>
<style>
.gtqc9hhus {
  d: path("M11.4 21.5H4.5v-19h15V12");
}

.k41-wijft {
  d: path("m7.5 9.25l4.5-3.5l4.5 3.5ZM8 12.5h7.6m-7.6 3h3.4m4.35 2l1.5-2.75c.5-.5 1.5-.25 1.5.5v1.5h1.5a1 1 0 0 1 1 1l-.5 2.5a1 1 0 0 1-1 .75h-4Zm-1.5 0V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
