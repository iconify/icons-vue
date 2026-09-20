<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb2r0lzlb.css';
import '../../css/w/wnkunhbrw.css';
import '../../css/z/zsn627f2e.css';
import '../../css/i/ih0_krdyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGtXESPbKf" x1="211.4" x2="330.3" y1="166.7" y2="372.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="cb2r0lzlb"/><stop offset=".5" class="cb2r0lzlb"/><stop offset="1" class="wnkunhbrw"/></linearGradient></defs><path class="zsn627f2e"/><path fill="url(#SVGtXESPbKf)" class="ih0_krdyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:moon-waxing-crescent-fill" /></template>
