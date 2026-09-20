<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lhrb43bwj.css';
import '../../css/a/aen-br9nh.css';
import '../../css/m/mal8l-ftc.css';
import '../../css/x/xc6kd3g1x.css';
import '../../css/l/l2u6evb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lhrb43bwj"/><path class="aen-br9nh"/><path class="mal8l-ftc"/><path class="xc6kd3g1x"/><path clip-rule="evenodd" class="l2u6evb2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-outline" /></template>
