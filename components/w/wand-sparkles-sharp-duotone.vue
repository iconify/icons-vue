<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yrcm1ibvg.css';
import '../../css/m/mus5l3b9c.css';
import '../../css/y/y9_9cbcfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yrcm1ibvg"/><path class="mus5l3b9c"/><path class="y9_9cbcfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sparkles-sharp-duotone" /></template>
