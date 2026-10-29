<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z4jtr5b1e.css';
import '../../css/a/al8--bbwn.css';
import '../../css/f/fdhlmacdj.css';
import '../../css/v/vfghup6ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z4jtr5b1e"/><path class="al8--bbwn wm-k"/><path class="fdhlmacdj wm-k"/><path class="vfghup6ai wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-pine-sketch" /></template>
