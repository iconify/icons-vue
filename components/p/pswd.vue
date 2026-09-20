<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2dprbyh.css';
import '../../css/l/l53bstutc.css';
import '../../css/g/g_b_kc2jc.css';
import '../../css/d/dwng4n9wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGA3uIndnJ" x1="256" x2="256" y1="514" y2="2" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="hv2dprbyh"/><stop offset="1" class="l53bstutc"/></linearGradient><path fill="url(#SVGA3uIndnJ)" class="g_b_kc2jc"/><path fill="url(#SVGA3uIndnJ)" class="dwng4n9wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pswd" /></template>
