<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nqee42z0q.css';
import '../../css/e/e_b8esyyo.css';
import '../../css/n/nt4x22b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nqee42z0q"/><path class="e_b8esyyo"/><path class="nt4x22b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:tunnel" /></template>
