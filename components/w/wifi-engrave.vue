<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oyy_ozbcu.css';
import '../../css/d/dgd2b7dnc.css';
import '../../css/c/cvygwcb1l.css';
import '../../css/a/a5ognjdal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oyy_ozbcu"/><path class="dgd2b7dnc wm-shadow"/><path class="cvygwcb1l"/><path class="a5ognjdal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wifi-engrave" /></template>
