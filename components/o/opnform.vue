<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5wc1_b_q.css';
import '../../css/d/dr8f4qvxq.css';
import '../../css/p/p220ddb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGqMIURdZM" x1="256" x2="256" y1="7.8" y2="504.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="h5wc1_b_q"/><stop offset="1" class="dr8f4qvxq"/></linearGradient><path fill="url(#SVGqMIURdZM)" class="p220ddb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opnform" /></template>
