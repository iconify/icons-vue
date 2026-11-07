<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hws41otvx.css';
import '../../css/d/dplkn_mxv.css';
import '../../css/f/fhnye3b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hws41otvx"/><path class="dplkn_mxv"/><path class="fhnye3b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-ring-broken" /></template>
