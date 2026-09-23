<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yrcm1ibvg.css';
import '../../css/w/w8rvhyi2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yrcm1ibvg"/><path class="w8rvhyi2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sparkles-sharp-fill" /></template>
