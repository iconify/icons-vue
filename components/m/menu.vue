<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv0c39bkq.css';
import '../../css/o/ot_1jemuk.css';
import '../../css/t/thdwmfbdd.css';
import '../../css/s/s650lobwr.css';
import '../../css/w/wz_ct64-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGQXQnRcgA" x1="10" x2="14" y1="5" y2="19" gradientUnits="userSpaceOnUse"><stop offset="0" class="sv0c39bkq"/><stop offset=".4" class="sv0c39bkq"/><stop offset="1" class="ot_1jemuk"/></linearGradient></defs><path class="thdwmfbdd wm-k"/><path class="s650lobwr wm-deco"/><path fill="url(#SVGQXQnRcgA)" class="wm-k wz_ct64-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:menu" /></template>
