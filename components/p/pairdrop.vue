<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzdtuh_ya.css';
import '../../css/d/djsc_abcb.css';
import '../../css/g/gkcfldb9j.css';
import '../../css/g/gevok0bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGL34muc6R" x1="1.3" x2="510.7" y1="403" y2="109" gradientUnits="userSpaceOnUse"><stop offset="0" class="mzdtuh_ya"/><stop offset="1" class="djsc_abcb"/></linearGradient><path fill="url(#SVGL34muc6R)" class="gkcfldb9j"/><path class="gevok0bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pairdrop" /></template>
