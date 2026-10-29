<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j1w5ydbfp.css';
import '../../css/r/rxu9rsydk.css';
import '../../css/p/pd2dgpb5t.css';
import '../../css/c/ctaobdbfw.css';
import '../../css/z/zpd26ob0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j1w5ydbfp wm-k"/><path class="rxu9rsydk wm-a"/><path class="pd2dgpb5t wm-shadow"/><path class="ctaobdbfw wm-k"/><path class="wm-a zpd26ob0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:notebook-engrave" /></template>
