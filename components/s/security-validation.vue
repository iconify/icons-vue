<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qlu0ufjal.css';
import '../../css/s/sb7awif1l.css';
import '../../css/u/uebd-hbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qlu0ufjal"/><path class="sb7awif1l"/><path class="uebd-hbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:security-validation" /></template>
