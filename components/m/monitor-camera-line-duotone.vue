<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uz-6ybbfc.css';
import '../../css/y/yvkryzb6g.css';
import '../../css/e/evvnrpb1m.css';
import '../../css/t/ta0zdfd_y.css';
import '../../css/w/wqwkkfban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uz-6ybbfc"/><path class="yvkryzb6g"/><path class="evvnrpb1m"/><path class="ta0zdfd_y"/><path class="wqwkkfban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-camera-line-duotone" /></template>
