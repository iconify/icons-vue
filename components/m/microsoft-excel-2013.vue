<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dab7n5b6s.css';
import '../../css/b/b09xt9blt.css';
import '../../css/v/vxn_s1bui.css';
import '../../css/p/p5m1hebpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGCFU3re6Y" x1="256" x2="256" y1="14.3" y2="497.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="dab7n5b6s"/><stop offset="1" class="b09xt9blt"/></linearGradient><path fill="url(#SVGCFU3re6Y)" class="vxn_s1bui"/><path class="p5m1hebpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2013" /></template>
