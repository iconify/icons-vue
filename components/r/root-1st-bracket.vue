<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s9fynmwrw.css';
import '../../css/z/ztw77h30a.css';
import '../../css/w/ws3epobig.css';
import '../../css/d/dpiq2xgfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s9fynmwrw"/><path class="ztw77h30a"/><path class="ws3epobig"/><path class="dpiq2xgfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:root-1st-bracket" /></template>
