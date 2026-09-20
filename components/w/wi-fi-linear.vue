<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nx9b_s0ui.css';
import '../../css/i/ip_zkkjah.css';
import '../../css/r/rna54ibnn.css';
import '../../css/g/g40pzzt0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nx9b_s0ui"/><path class="ip_zkkjah"/><path class="rna54ibnn"/><path class="g40pzzt0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-linear" /></template>
