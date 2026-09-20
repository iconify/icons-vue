<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxzlx69ao.css';
import '../../css/f/f2mdsnbel.css';
import '../../css/w/wqzu09b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGhf8rIb8z" x1="-2.909" x2="1343.613" y1="257" y2="257" gradientTransform="matrix(1 0 0 -1 0 513)" gradientUnits="userSpaceOnUse"><stop offset="0" class="pxzlx69ao"/><stop offset="1" class="f2mdsnbel"/></linearGradient><path fill="url(#SVGhf8rIb8z)" class="wqzu09b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:simplelogin" /></template>
