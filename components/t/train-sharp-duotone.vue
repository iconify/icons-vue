<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/d094f7bjn.css';
import '../../css/p/pzpi_ibpg.css';
import '../../css/j/j3akw_70p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d094f7bjn"/><path class="pzpi_ibpg"/><path class="j3akw_70p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-sharp-duotone" /></template>
