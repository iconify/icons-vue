<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ibrcm0b3s.css';
import '../../css/w/wdipljbrd.css';
import '../../css/x/xsl5v7bfz.css';
import '../../css/u/udovdvbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ibrcm0b3s"/><path class="wdipljbrd"/><path class="xsl5v7bfz"/><path class="udovdvbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-4-bold" /></template>
