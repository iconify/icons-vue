<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r2s6slf0j.css';
import '../../css/g/g92_1ls8c.css';
import '../../css/q/q-d3abbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r2s6slf0j"/><path class="g92_1ls8c"/><path class="q-d3abbgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-vertical-line-duotone" /></template>
