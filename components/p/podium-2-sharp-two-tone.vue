<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lid049njr.css';
import '../../css/x/xeb-fib6w.css';
import '../../css/m/mhv0dr0xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lid049njr"/><path class="xeb-fib6w"/><path class="mhv0dr0xk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-2-sharp-two-tone" /></template>
