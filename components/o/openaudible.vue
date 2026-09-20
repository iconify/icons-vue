<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhrs64bsk.css';
import '../../css/m/m3ytibb1b.css';
import '../../css/m/mfuh3fbwr.css';
import '../../css/k/kxr93cbsn.css';
import '../../css/b/bov0584ws.css';
import '../../css/i/i74u_tb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGEl7m4dhk" x1="256" x2="256" y1="-2.388" y2="441.6" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xhrs64bsk"/><stop offset=".25" class="m3ytibb1b"/><stop offset=".758" class="mfuh3fbwr"/><stop offset="1" class="kxr93cbsn"/></linearGradient><path fill="url(#SVGEl7m4dhk)" class="bov0584ws"/><path class="i74u_tb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openaudible" /></template>
