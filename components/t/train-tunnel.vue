<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/au7a6tb1g.css';
import '../../css/a/a4g2qzb3h.css';
import '../../css/t/txxzuzbwv.css';
import '../../css/i/ieb9-qkpx.css';
import '../../css/p/pxz1_zber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="au7a6tb1g"/><path class="a4g2qzb3h"/><path class="txxzuzbwv"/><path class="ieb9-qkpx"/><path class="pxz1_zber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:train-tunnel" /></template>
