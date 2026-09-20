<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hgrm2rbfz.css';
import '../../css/r/rrxhurnze.css';
import '../../css/c/c9dh15yvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hgrm2rbfz"/><path class="rrxhurnze"/><path class="c9dh15yvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-pen-linear" /></template>
