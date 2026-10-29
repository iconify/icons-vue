<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nw2db5r7p.css';
import '../../css/o/ojkty0bym.css';
import '../../css/z/z3jjry8bb.css';
import '../../css/l/lptx1rgle.css';
import '../../css/z/z93dh598w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nw2db5r7p wm-k"/><path class="ojkty0bym wm-a"/><path class="wm-shadow z3jjry8bb"/><path class="lptx1rgle wm-k"/><path class="wm-a z93dh598w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toilet-engrave" /></template>
