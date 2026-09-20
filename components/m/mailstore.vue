<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcrl3bcgy.css';
import '../../css/i/iek9glb2w.css';
import '../../css/s/sij7iobyd.css';
import '../../css/r/rjboz-k8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG6NS9keyK" x1="-809.442" x2="-777.12" y1="16.767" y2="16.767" gradientTransform="rotate(231.815 -6008.486 -2785.216)scale(15.4281)" gradientUnits="userSpaceOnUse"><stop offset="0" class="lcrl3bcgy"/><stop offset="1" class="iek9glb2w"/></linearGradient><path fill="url(#SVG6NS9keyK)" class="sij7iobyd"/><path class="rjboz-k8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailstore" /></template>
