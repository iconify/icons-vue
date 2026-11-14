<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2-jo08zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:step-out" /></template>
<style>
.c2-jo08zx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m21.03 4.47l-3-3q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T16.75 2t.057.287t.163.243l1.719 1.72H13.5q-1.76 0-3.005 1.245T9.25 8.5v4.75H7.5q-1.76 0-3.005 1.245T3.25 17.5v.5q0 1.76 1.245 3.005T7.5 22.25h5q1.76 0 3.005-1.245T16.75 18v-.5q0-1.76-1.245-3.005T12.5 13.25h-1.75V8.5q0-2.75 2.75-2.75h5.189L16.97 7.47q-.106.105-.163.243T16.75 8t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l3-3q.106-.105.163-.243T21.25 5t-.057-.287t-.163-.243");
}

</style>
