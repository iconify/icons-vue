<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xsiiobcvs.css';
import '../../css/i/iq0j3ibeh.css';
import '../../css/x/xdqw6obrh.css';
import '../../css/c/cjqmx4fpw.css';
import '../../css/t/tv2-46qgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xsiiobcvs"/><path class="iq0j3ibeh wm-a"/><path class="wm-shadow xdqw6obrh"/><path class="cjqmx4fpw wm-k"/><path class="tv2-46qgh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trending-down-engrave" /></template>
