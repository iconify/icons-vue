<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf_jm769q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-left-2-rounded" /></template>
<style>
.cf_jm769q {
  fill: currentColor;
  d: path("M11.825 21q-.504 0-.948-.186t-.812-.554L5.59 15.796q-.18-.179-.185-.447t.198-.453l.017-.017q.227-.208.515-.268q.287-.061.581.012l2.785.687V7q0-.213.143-.357T10 6.5t.357.143T10.5 7v7.27h1.827V5.5q0-.213.143-.357T12.827 5t.357.143t.143.357v8.77h1.846V11.5q0-.213.143-.357t.357-.143t.357.143t.143.357v2.77H18v-.77q0-.213.143-.357T18.5 13t.357.143t.143.357v4q0 1.458-1.021 2.479T15.5 21zM4.1 6.5h2.842q.19 0 .317.126q.126.126.126.316t-.126.317t-.317.126H3.808q-.348 0-.578-.23T3 6.577V3.442q0-.19.126-.316T3.442 3t.317.126t.126.316v2.064q1.992-1.533 4.013-2.279t4.16-.746q2.719 0 4.987 1.111t3.52 2.987q.093.16.057.335t-.195.261q-.16.087-.332.044t-.27-.202Q18.61 5.314 16.562 4.34t-4.504-.974q-2.085 0-4.052.775T4.1 6.5");
}

</style>
