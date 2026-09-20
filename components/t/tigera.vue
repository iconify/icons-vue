<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy7_7wa8u.css';
import '../../css/e/e507l5bmm.css';
import '../../css/c/cnmlbv_ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGp4mlkcnW" x1="0" x2="512" y1="257.97" y2="257.97" gradientTransform="matrix(1 0 0 -1 0 513.97)" gradientUnits="userSpaceOnUse"><stop offset="0" class="gy7_7wa8u"/><stop offset="1" class="e507l5bmm"/></linearGradient><path fill="url(#SVGp4mlkcnW)" class="cnmlbv_ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tigera" /></template>
