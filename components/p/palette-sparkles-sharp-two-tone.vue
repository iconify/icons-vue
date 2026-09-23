<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yzx0mb0bw.css';
import '../../css/t/t8m6ab_md.css';
import '../../css/i/i4pr7mb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yzx0mb0bw"/><path class="t8m6ab_md"/><path class="i4pr7mb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:palette-sparkles-sharp-two-tone" /></template>
