<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xodd2wf-l.css';
import '../../css/z/z7-jgccde.css';
import '../../css/w/w7lt636is.css';
import '../../css/w/wcute_4vd.css';
import '../../css/c/c4_wodreq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xodd2wf-l"/><path class="wm-a z7-jgccde"/><path class="w7lt636is wm-shadow"/><path class="wcute_4vd wm-k"/><path class="c4_wodreq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thermometer-engrave" /></template>
