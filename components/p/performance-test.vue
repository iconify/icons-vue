<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txczzpbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:performance-test" /></template>
<style>
.txczzpbvg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.107 9.108Q2.251 11.962 2.25 16q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.052.113.094q.062.041.13.069t.14.043t.147.014h18q.065 0 .13-.011q.064-.012.125-.034q.062-.022.118-.054q.057-.033.107-.075t.092-.091t.075-.106t.056-.118t.035-.125q.012-.067.012-.136q-.001-4.038-2.857-6.892Q16.038 6.253 12 6.253T5.107 9.108M13.5 15.25l3.6-4.8q.09-.119.127-.264q.037-.144.015-.292t-.097-.276t-.195-.218q-.059-.044-.126-.076q-.066-.032-.138-.051q-.071-.018-.145-.022t-.147.007t-.143.034q-.07.025-.133.063q-.064.037-.119.087t-.099.108l-4.275 5.7H3.78q.241-2.936 2.387-5.082Q8.584 7.753 12 7.753t5.833 2.415q2.146 2.146 2.387 5.082z");
}

</style>
