<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubecpob4l.css';
import '../../css/n/nsmhn8bij.css';
import '../../css/h/hzhb0bcwn.css';
import '../../css/p/p54c8n9ij.css';
import '../../css/w/wqg2sgbzb.css';
import '../../css/h/hftppjblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ubecpob4l"/><path class="nsmhn8bij"/><g class="hzhb0bcwn"><path class="p54c8n9ij"/><path class="wqg2sgbzb"/><path class="hftppjblv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:saw" /></template>
