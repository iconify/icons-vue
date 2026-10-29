<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q9t9x2f9r.css';
import '../../css/y/y8jl16c_k.css';
import '../../css/f/fmn_qacoy.css';
import '../../css/r/rzoychbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q9t9x2f9r wm-k"/><path class="wm-shadow y8jl16c_k"/><path class="fmn_qacoy wm-k"/><path class="rzoychbjy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ruler-engrave" /></template>
