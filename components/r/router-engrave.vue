<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hrc3voxan.css';
import '../../css/k/kdj-p2bid.css';
import '../../css/s/s8d0q6baj.css';
import '../../css/f/frsup1bzk.css';
import '../../css/n/n5a7qlyhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hrc3voxan wm-k"/><path class="kdj-p2bid wm-a"/><path class="s8d0q6baj wm-shadow"/><path class="frsup1bzk wm-k"/><path class="n5a7qlyhu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:router-engrave" /></template>
