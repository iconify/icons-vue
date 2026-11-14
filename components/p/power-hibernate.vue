<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqbkepvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-hibernate" /></template>
<style>
.fiqbkepvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 5q.381.259.73.56q.348.302.66.641t.583.712t.497.775t.405.826q.178.425.307.867q.129.443.206.897t.101.915m-7.069 8.368q-.479.056-.961.053q-.483-.002-.961-.063q-.478-.06-.946-.177q-.468-.118-.918-.291q-.45-.172-.877-.398q-.426-.226-.822-.501t-.756-.596t-.679-.682q-.14-.159-.272-.325q-.132-.167-.254-.34q-.123-.173-.236-.352t-.217-.364t-.198-.375t-.177-.386t-.156-.394t-.136-.401t-.114-.409q-.051-.205-.092-.414q-.041-.208-.07-.418t-.048-.421t-.025-.423q-.008-.212-.004-.424q.005-.212.02-.424q.015-.211.042-.422q.026-.21.064-.419q.037-.208.086-.415q.049-.206.108-.41q.06-.203.13-.403q.07-.201.151-.397t.171-.387t.192-.378t.212-.368t.231-.355t.249-.343q.13-.168.268-.329t.284-.315q.146-.153.3-.299q.155-.146.316-.283q.162-.137.331-.265Q5.825 5.119 6 5m4.5-2.5V10m9.5 4.5a4 4 0 1 0 1.5 5.5a3.25 3.25 0 0 1-1.5-5.5Z");
}

</style>
