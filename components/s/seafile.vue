<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwsqs5bzr.css';
import '../../css/b/b0ea5lb7o.css';
import '../../css/j/j48clrlca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGtHKZNdYr" x1="256" x2="256" y1="91.1" y2="421.1" gradientUnits="userSpaceOnUse"><stop offset="0" class="lwsqs5bzr"/><stop offset="1" class="b0ea5lb7o"/></linearGradient><path fill="url(#SVGtHKZNdYr)" class="j48clrlca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seafile" /></template>
