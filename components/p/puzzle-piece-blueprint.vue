<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/wt0aips9s.css';
import '../../css/b/bm-lo_bnm.css';
import '../../css/m/m_gxpcbfh.css';
import '../../css/h/hpy0y4b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco wt0aips9s"/><path class="bm-lo_bnm wm-deco"/><path class="m_gxpcbfh wm-deco"/><path class="hpy0y4b9v wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:puzzle-piece-blueprint" /></template>
