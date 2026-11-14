<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va51w2bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:service-braille" /></template>
<style>
.va51w2bqj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.926q.046.041.09.086q.586.586.586 1.414t-.586 1.414t-1.414.586q-2 0-2-2q0-1.711 1.463-1.958q-.963-.664-.963-2.292v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zM9.75 9.25q1.5 0 1.5 1.5t-1.5 1.5t-1.5-1.5t1.5-1.5m3 5.25q0-1.5 1.5-1.5t1.5 1.5t-1.5 1.5t-1.5-1.5m-.5 3.75q0-2 2-2q.828 0 1.414.586t.586 1.414t-.586 1.414t-1.414.586q-2 0-2-2m-2.5-5.75q2 0 2 2t-2 2t-2-2t2-2m0 4.25q1.5 0 1.5 1.5t-1.5 1.5t-1.5-1.5t1.5-1.5");
}

</style>
