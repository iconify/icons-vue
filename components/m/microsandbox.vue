<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wifo-cb2s.css';
import '../../css/w/wqp-bwb_c.css';
import '../../css/d/dm_mfnb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGwONFndEi" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="wifo-cb2s"/><stop offset="1" class="wqp-bwb_c"/></linearGradient><path fill="url(#SVGwONFndEi)" class="dm_mfnb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsandbox" /></template>
