<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/ke6pb1bjn.css';
import '../../css/g/gxpdn9-wz.css';
import '../../css/v/vazvq7ahv.css';
import '../../css/r/rcjmc3bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ke6pb1bjn"/><path class="gxpdn9-wz"/><path class="vazvq7ahv"/><path class="rcjmc3bzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:peace-hand" /></template>
