<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f3r-8yyut.css';
import '../../css/a/att42bbkg.css';
import '../../css/j/j_vnhybnm.css';
import '../../css/r/rri6uechc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f3r-8yyut"/><path class="att42bbkg wm-shadow"/><path class="j_vnhybnm"/><path class="rri6uechc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thandai-engrave" /></template>
