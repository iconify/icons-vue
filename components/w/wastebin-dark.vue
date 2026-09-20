<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fef2p4b2l.css';
import '../../css/r/r2rl9cbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG6BpB5cBi" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="fef2p4b2l"/><stop offset="1"/></linearGradient><path fill="url(#SVG6BpB5cBi)" class="r2rl9cbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wastebin-dark" /></template>
