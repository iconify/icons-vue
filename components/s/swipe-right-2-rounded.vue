<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ya7zbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-right-2-rounded" /></template>
<style>
.y9ya7zbgi {
  fill: currentColor;
  d: path("M11.825 21q-.504 0-.948-.186t-.812-.554L5.59 15.796q-.18-.179-.185-.447t.198-.453l.017-.017q.227-.208.515-.268q.287-.061.581.012l2.785.687V7q0-.213.143-.357T10 6.5t.357.143T10.5 7v7.27h1.827V10.5q0-.213.143-.357t.357-.143t.357.143t.143.357v3.77h1.846V11.5q0-.213.143-.357t.357-.143t.357.143t.143.357v2.77H18v-.77q0-.213.143-.357T18.5 13t.357.143t.143.357v4q0 1.458-1.021 2.479T15.5 21zm5.233-13.615q-.19 0-.317-.126q-.125-.126-.125-.317q0-.19.125-.316q.126-.126.317-.126H19.9q-1.938-1.585-3.906-2.36t-4.052-.775q-2.455 0-4.503.974T4.175 7.017q-.098.16-.27.202t-.332-.044t-.195-.261t.056-.335q1.252-1.875 3.52-2.987t4.988-1.111q2.139 0 4.16.746t4.013 2.279V3.442q0-.19.126-.316T20.558 3t.316.126t.126.316v3.135q0 .348-.23.578t-.578.23z");
}

</style>
