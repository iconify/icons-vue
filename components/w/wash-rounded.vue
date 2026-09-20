<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu5s2obzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wash-rounded" /></template>
<style>
.pu5s2obzn {
  fill: currentColor;
  d: path("M6.5 21q-1.458 0-2.479-.906Q3 19.19 3 17.731v-4.939q0-.645.302-1.196q.301-.552.842-.905l7.785-5.033q.121-.08.296-.08q.175-.001.304.128q.365.365.337.793t-.287.855l-1.702 2.838H18.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H13v2.27h7.5q.213 0 .356.144t.144.356t-.144.356t-.356.144H13v2.269h6.5q.213 0 .356.144t.144.356t-.144.356t-.356.144H13V20h4.5q.213 0 .356.144t.144.357t-.144.356T17.5 21zm9.878-13.593q-.609-.614-.609-1.397q0-.904.571-1.775t1.112-1.554q.126-.162.315-.162t.32.162q.54.684 1.111 1.552t.571 1.786q0 .78-.61 1.39q-.611.61-1.392.61t-1.389-.613");
}

</style>
