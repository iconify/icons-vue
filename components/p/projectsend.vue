<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg4p2bc8g.css';
import '../../css/p/p92lynpoq.css';
import '../../css/l/lkv5ngb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGpE1RZbAk" x1="77.2" x2="414" y1="424" y2="98.7" gradientUnits="userSpaceOnUse"><stop offset=".168" class="qg4p2bc8g"/><stop offset=".813" class="p92lynpoq"/></linearGradient><path fill="url(#SVGpE1RZbAk)" class="lkv5ngb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:projectsend" /></template>
