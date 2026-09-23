<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lvgzmebcf.css';
import '../../css/v/vy-nx7bhq.css';
import '../../css/s/skqfcdqhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lvgzmebcf"/><path class="vy-nx7bhq"/><path class="skqfcdqhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zap-sparkles-sharp-two-tone" /></template>
