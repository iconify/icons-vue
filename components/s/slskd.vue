<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njy-ywcwy.css';
import '../../css/l/l_shvbb8k.css';
import '../../css/g/gkcr4nuis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGDxufMddq" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="njy-ywcwy"/><stop offset="1" class="l_shvbb8k"/></linearGradient><path fill="url(#SVGDxufMddq)" class="gkcr4nuis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slskd" /></template>
