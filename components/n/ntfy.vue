<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-txusbyn.css';
import '../../css/i/i43qr5u2f.css';
import '../../css/i/i04a-1b-v.css';
import '../../css/q/qh-dmzbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGrmC2ElnH" x1="21.8" x2="445.2" y1="74.4" y2="393.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="z-txusbyn"/><stop offset="1" class="i43qr5u2f"/></linearGradient><path fill="url(#SVGrmC2ElnH)" class="i04a-1b-v"/><path class="qh-dmzbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ntfy" /></template>
