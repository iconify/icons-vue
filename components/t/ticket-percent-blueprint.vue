<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/njvgg9mnp.css';
import '../../css/r/rhnsbwb-m.css';
import '../../css/n/nwncmym7l.css';
import '../../css/s/sq9ejvb2i.css';
import '../../css/w/wfkhky_vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="njvgg9mnp wm-deco"/><path class="rhnsbwb-m wm-deco"/><path class="nwncmym7l wm-k"/><path class="sq9ejvb2i wm-a"/><path class="wfkhky_vc wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ticket-percent-blueprint" /></template>
