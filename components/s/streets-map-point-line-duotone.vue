<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/l/loa18gbiz.css';
import '../../css/d/dijqohbja.css';
import '../../css/a/a9qq5obmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="loa18gbiz"/><path class="dijqohbja"/><path class="a9qq5obmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-line-duotone" /></template>
