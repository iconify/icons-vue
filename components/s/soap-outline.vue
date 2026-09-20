<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmz20mbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soap-outline" /></template>
<style>
.rmz20mbhb {
  fill: currentColor;
  d: path("M15.06 7.462q-.368-.365-.368-.882t.365-.885t.882-.368t.885.365t.368.882t-.365.885t-.882.368t-.885-.365m3.893.104q-.434-.433-.434-1.066t.434-1.066Q19.387 5 20.019 5t1.067.434q.433.433.433 1.066t-.433 1.066T20.019 8t-1.066-.434m-2.16-3.626q-.293-.291-.293-.707t.291-.709t.707-.293t.709.29t.293.708t-.291.708t-.707.294t-.709-.291M6.5 21q-1.458 0-2.479-.906Q3 19.19 3 17.731v-4.939q0-.645.302-1.196q.301-.552.842-.905l8.116-5.255l.115.116q.366.365.415.87t-.211.932l-1.702 2.838H18.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H9.104l2.483-4.138L4.7 11.519q-.321.202-.51.542q-.19.341-.19.731v4.939q0 1.036.734 1.653Q5.47 20 6.5 20h11q.213 0 .356.144t.144.357t-.144.356T17.5 21zm6.5-6.539v-1h7.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zm0 3.27v-1h6.5q.213 0 .356.144t.144.356t-.144.356t-.356.144zm-4.5-3.27");
}

</style>
