<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv0c39bkq.css';
import '../../css/o/ot_1jemuk.css';
import '../../css/i/i74c86fod.css';
import '../../css/w/wn_xqp0lg.css';
import '../../css/v/vltqu1bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGMhffHckf" x1="10" x2="14" y1="2.5" y2="21.74" gradientUnits="userSpaceOnUse"><stop offset="0" class="sv0c39bkq"/><stop offset=".4" class="sv0c39bkq"/><stop offset="1" class="ot_1jemuk"/></linearGradient></defs><path class="i74c86fod wm-k"/><path class="wm-deco wn_xqp0lg"/><path fill="url(#SVGMhffHckf)" class="vltqu1bwp wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:tornado" /></template>
