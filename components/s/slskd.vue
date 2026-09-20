<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njy-ywcwy.css';
import '../../css/l/l_shvbb8k.css';
import '../../css/g/gkcr4nuis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGicWhed2p" x1="0" x2="512" y1="534" y2="534" gradientTransform="translate(0 -278)" gradientUnits="userSpaceOnUse"><stop offset="0" class="njy-ywcwy"/><stop offset="1" class="l_shvbb8k"/></linearGradient><path fill="url(#SVGicWhed2p)" class="gkcr4nuis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slskd" /></template>
