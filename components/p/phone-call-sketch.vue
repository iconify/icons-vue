<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cn2v9_bei.css';
import '../../css/f/f1o7adbih.css';
import '../../css/y/y2ih3rbsr.css';
import '../../css/a/aqkf81bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cn2v9_bei"/><path class="f1o7adbih wm-s"/><path class="wm-k y2ih3rbsr"/><path class="aqkf81bgs wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-call-sketch" /></template>
