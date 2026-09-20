<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzdtuh_ya.css';
import '../../css/d/djsc_abcb.css';
import '../../css/g/gkcfldb9j.css';
import '../../css/g/gevok0bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG1ULwzb7T" x1="1.309" x2="510.691" y1="403.046" y2="108.954" gradientUnits="userSpaceOnUse"><stop offset="0" class="mzdtuh_ya"/><stop offset="1" class="djsc_abcb"/></linearGradient><path fill="url(#SVG1ULwzb7T)" class="gkcfldb9j"/><path class="gevok0bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pairdrop" /></template>
