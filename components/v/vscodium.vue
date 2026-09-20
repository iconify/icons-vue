<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbj93mbti.css';
import '../../css/g/gcvz4cw5d.css';
import '../../css/u/u74v93ocj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGCm7E3RHI" x1="214.46" x2="709.401" y1="309.438" y2="-168.11" gradientTransform="matrix(1 0 0 -1 -200 301)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tbj93mbti"/><stop offset="1" class="gcvz4cw5d"/></linearGradient><path fill="url(#SVGCm7E3RHI)" class="u74v93ocj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vscodium" /></template>
