<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezoa1_boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skin-type-dry" /></template>
<style>
.ezoa1_boi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.54 5.512C13.686 4.455 12.807 3.441 12 2.5c-3 3.5-7 8-7 12q0 .277.022.552m2.811 5.072q.449.333.945.591q.497.257 1.028.432t1.083.264T12 21.5q.172 0 .343-.008t.343-.026q.171-.017.341-.042t.339-.059q.168-.033.335-.075t.331-.091t.326-.108t.321-.124t.314-.139t.307-.155t.299-.169t.29-.184q.143-.095.281-.198q.138-.102.271-.211t.26-.224t.249-.237t.237-.249t.224-.26t.211-.271t.198-.281t.184-.29t.169-.299t.155-.307q.073-.155.139-.314t.124-.321t.108-.326t.091-.331q.042-.167.075-.335q.034-.169.059-.339t.042-.341t.026-.343Q19 14.672 19 14.5c0-1.39-.483-2.84-1.239-4.287M20.5 3.5l-17 17");
}

</style>
