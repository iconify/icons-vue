<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dammqr2-z.css';
import '../../css/y/yfr4u4d-v.css';
import '../../css/p/p8iis0b6r.css';
import '../../css/n/nsl_tfb_b.css';
import '../../css/w/wocyyxi5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dammqr2-z"/><path class="wm-k yfr4u4d-v"/><path class="p8iis0b6r wm-a"/><path class="nsl_tfb_b wm-k"/><path class="wm-a wocyyxi5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-search-sketch" /></template>
