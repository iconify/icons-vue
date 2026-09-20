<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm_ste21z.css';
import '../../css/m/m7rzspbge.css';
import '../../css/c/c6rjz91lt.css';
import '../../css/j/jbbtftbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGv5Xsmd0j" x1="256" x2="256" y1="14.331" y2="497.669" gradientUnits="userSpaceOnUse"><stop offset="0" class="gm_ste21z"/><stop offset="1" class="m7rzspbge"/></linearGradient><path fill="url(#SVGv5Xsmd0j)" class="c6rjz91lt"/><path class="jbbtftbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2013" /></template>
