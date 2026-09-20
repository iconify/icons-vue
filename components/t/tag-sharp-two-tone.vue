<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xlocvhbhg.css';
import '../../css/o/oy_qfibdp.css';
import '../../css/s/s1f4hpnzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xlocvhbhg"/><path class="oy_qfibdp"/><path class="s1f4hpnzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-sharp-two-tone" /></template>
