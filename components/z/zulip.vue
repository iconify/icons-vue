<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8z4pn8gg.css';
import '../../css/e/ep_fppbyz.css';
import '../../css/s/s-blenb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGqRZSBeaL" x1="-49.204" x2="-49.204" y1="653.298" y2="652.538" gradientTransform="matrix(603.92 0 0 -673.14 29971.352 439761.281)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x8z4pn8gg"/><stop offset="1" class="ep_fppbyz"/></linearGradient><path fill="url(#SVGqRZSBeaL)" class="s-blenb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zulip" /></template>
