<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_qts-b_r.css';
import '../../css/k/krzr9662y.css';
import '../../css/z/zmtq5epxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGWGaCTY5P" x1="-695.575" x2="-519.089" y1="422.325" y2="327.556" gradientTransform="rotate(105 1263.193 108.382)scale(-2.8347 2.8347)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="p_qts-b_r"/></linearGradient><path fill="url(#SVGWGaCTY5P)" class="krzr9662y"/><path class="zmtq5epxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:re-command-dark" /></template>
