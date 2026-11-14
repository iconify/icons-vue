<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is9mivb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:report-table" /></template>
<style>
.is9mivb7e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.588q.338.581.338 1.5v6.5q0 .065-.002.128q.002.06.002.122q0 2.25-2.25 2.25H9q-2.25 0-2.25-2.25q0-.062.002-.122q-.002-.063-.002-.128v-6.5q0-2.5 2.5-2.5h3.933q-.433-.658-.433-1.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163z");
}

</style>
