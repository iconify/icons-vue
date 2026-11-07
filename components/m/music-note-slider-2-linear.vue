<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b-bymobfb.css';
import '../../css/n/nog5ftwkf.css';
import '../../css/t/tnljxhbrz.css';
import '../../css/l/lz7c3lbwd.css';
import '../../css/b/bozgg201l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b-bymobfb"/><path class="nog5ftwkf"/><path class="tnljxhbrz"/><path class="lz7c3lbwd"/><path class="bozgg201l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-slider-2-linear" /></template>
