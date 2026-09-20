<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tze8xacps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wash-outline" /></template>
<style>
.tze8xacps {
  fill: currentColor;
  d: path("M16.378 7.409q-.609-.61-.609-1.391q0-.7.46-1.58t1.54-2.15q1.081 1.27 1.54 2.15t.46 1.58q0 .78-.61 1.39q-.611.611-1.392.611t-1.389-.61M6.5 21q-1.458 0-2.479-.906Q3 19.19 3 17.731v-4.939q0-.645.302-1.196q.301-.552.842-.905l8.116-5.255l.115.116q.366.365.415.87t-.211.932l-1.702 2.838H18.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H9.104l2.483-4.138L4.7 11.519q-.321.202-.51.542q-.19.341-.19.731v4.939q0 1.036.734 1.653Q5.47 20 6.5 20h11q.213 0 .356.144t.144.357t-.144.356T17.5 21zm6.5-6.539v-1h7.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zm0 3.27v-1h6.5q.213 0 .356.144t.144.356t-.144.356t-.356.144zm-4.5-3.27");
}

</style>
