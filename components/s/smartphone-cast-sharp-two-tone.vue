<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/u/uu2ywi0jh.css';
import '../../css/d/dzmd--vds.css';
import '../../css/o/oj7ascbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uu2ywi0jh"/><path class="dzmd--vds"/><path class="oj7ascbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-cast-sharp-two-tone" /></template>
