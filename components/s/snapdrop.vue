<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz9e28b4s.css';
import '../../css/z/zf3-23bwg.css';
import '../../css/y/y5opfbb7y.css';
import '../../css/x/xdnv-n33c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGCMhNRbNM" x1="256" x2="256" y1="496.7" y2="19.2" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rz9e28b4s"/><stop offset=".599" class="zf3-23bwg"/><stop offset="1" class="y5opfbb7y"/></linearGradient><path fill="url(#SVGCMhNRbNM)" class="xdnv-n33c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapdrop" /></template>
