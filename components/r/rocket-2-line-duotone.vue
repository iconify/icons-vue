<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qj2-a9byh.css';
import '../../css/l/l40gmibpr.css';
import '../../css/c/ck_1iolbp.css';
import '../../css/j/j50gegbkk.css';
import '../../css/o/ohbg_acuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qj2-a9byh"/><path class="l40gmibpr"/><path class="ck_1iolbp"/><path class="j50gegbkk"/><path class="ohbg_acuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-2-line-duotone" /></template>
