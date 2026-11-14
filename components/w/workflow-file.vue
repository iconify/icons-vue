<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms0179byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workflow-file" /></template>
<style>
.ms0179byg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zM9 5.5q1.036 0 1.768.732T11.5 8t-.732 1.768q-.452.451-1.018.624v4.216q.566.173 1.018.624q.451.452.624 1.018h1.175Q12.908 14.5 15 14.5q1.036 0 1.768.732T17.5 17t-.732 1.768T15 19.5q-2.092 0-2.433-1.75h-1.175q-.173.566-.624 1.018q-.732.732-1.768.732q-2.5 0-2.5-2.5q0-2.092 1.75-2.433v-4.134Q6.5 10.092 6.5 8q0-2.5 2.5-2.5");
}

</style>
