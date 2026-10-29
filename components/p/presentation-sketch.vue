<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yeouzeolq.css';
import '../../css/m/mx6glt-_b.css';
import '../../css/h/hyx065bvb.css';
import '../../css/d/duf5upbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yeouzeolq"/><path class="mx6glt-_b wm-a"/><path class="hyx065bvb wm-k"/><path class="duf5upbxl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:presentation-sketch" /></template>
