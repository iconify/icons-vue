<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mfx2_82uq.css';
import '../../css/f/f0ff5koer.css';
import '../../css/b/b6t20tvst.css';
import '../../css/v/vw2d3v36t.css';
import '../../css/p/p3_r2hr6d.css';
import '../../css/z/z2cmsqfjo.css';
import '../../css/b/b12zfebmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mfx2_82uq wm-k"/><path class="f0ff5koer wm-a"/><path class="b6t20tvst wm-shadow"/><path class="vw2d3v36t wm-k"/><path class="p3_r2hr6d wm-a"/><path class="wm-k z2cmsqfjo"/><path class="b12zfebmf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-engrave" /></template>
