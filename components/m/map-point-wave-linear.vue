<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uh8evbbul.css';
import '../../css/v/vv52kbcqz.css';
import '../../css/q/qq--gqc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uh8evbbul"/><path class="vv52kbcqz"/><path class="qq--gqc6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-wave-linear" /></template>
