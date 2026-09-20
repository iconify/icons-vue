<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb2r0lzlb.css';
import '../../css/w/wnkunhbrw.css';
import '../../css/z/zsn627f2e.css';
import '../../css/w/wjmdxf2fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVG4UvJpbpD" x1="193.9" x2="327.1" y1="143.9" y2="374.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="cb2r0lzlb"/><stop offset=".5" class="cb2r0lzlb"/><stop offset="1" class="wnkunhbrw"/></linearGradient></defs><path class="zsn627f2e"/><path fill="url(#SVG4UvJpbpD)" class="wjmdxf2fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:moon-waxing-gibbous-fill" /></template>
