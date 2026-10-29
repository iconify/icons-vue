<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h6-v3pfiv.css';
import '../../css/h/hkeb9lbtu.css';
import '../../css/j/jsn461bcb.css';
import '../../css/d/d59m1yvcb.css';
import '../../css/e/e--mbmb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h6-v3pfiv wm-k"/><path class="hkeb9lbtu wm-a"/><path class="jsn461bcb wm-shadow"/><path class="d59m1yvcb wm-k"/><path class="e--mbmb3x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:signpost-engrave" /></template>
