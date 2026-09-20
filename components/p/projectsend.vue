<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg4p2bc8g.css';
import '../../css/p/p92lynpoq.css';
import '../../css/l/lkv5ngb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGKPp1AbrK" x1="82.165" x2="419.033" y1="678.269" y2="352.959" gradientTransform="translate(-5 -254.252)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="qg4p2bc8g"/><stop offset=".813" class="p92lynpoq"/></linearGradient><path fill="url(#SVGKPp1AbrK)" class="lkv5ngb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:projectsend" /></template>
