<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/raucetsey.css';
import '../../css/u/uor89vbsf.css';
import '../../css/z/zeiub32xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="raucetsey"/><path class="uor89vbsf"/><path class="zeiub32xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-vertical-bold" /></template>
