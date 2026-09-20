<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/nx22e_b0q.css';
import '../../css/o/oxyed4bhd.css';
import '../../css/i/ippy8g9bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nx22e_b0q"/><path class="oxyed4bhd"/><path class="ippy8g9bw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:palette-sharp-two-tone" /></template>
