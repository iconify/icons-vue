<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq4w-tbtk.css';
import '../../css/l/lea_bji6i.css';
import '../../css/e/e93no6iji.css';
import '../../css/n/njpesabrm.css';
import '../../css/r/rz09ydx7m.css';
import '../../css/s/sdzoy8bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGVY1lkber" cx="83.8" cy="68" r="128" gradientUnits="userSpaceOnUse"><stop offset="0" class="wq4w-tbtk"/><stop offset=".85" class="lea_bji6i"/><stop offset="1" class="lea_bji6i"/></radialGradient></defs><path class="e93no6iji"/><path fill="url(#SVGVY1lkber)" transform="matrix(2.7 0 0 2.7 -18.389 -18.389)" class="njpesabrm"/><path class="rz09ydx7m"/><path class="sdzoy8bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:trident-emblem" /></template>
