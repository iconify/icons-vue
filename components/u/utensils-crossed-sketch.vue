<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ofv9jmb_s.css';
import '../../css/g/gyxdggaoa.css';
import '../../css/r/r7pcl4hir.css';
import '../../css/s/sxknq0szb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ofv9jmb_s wm-k"/><path class="gyxdggaoa wm-a"/><path class="r7pcl4hir wm-k"/><path class="sxknq0szb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:utensils-crossed-sketch" /></template>
