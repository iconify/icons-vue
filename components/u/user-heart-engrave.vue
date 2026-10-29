<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/is7p6owsa.css';
import '../../css/q/qpvrooc1e.css';
import '../../css/f/fdic79byo.css';
import '../../css/l/ljeitrr-k.css';
import '../../css/v/vi7r50kxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="is7p6owsa wm-k"/><path class="qpvrooc1e wm-s"/><path class="fdic79byo wm-shadow"/><path class="ljeitrr-k wm-k"/><path class="vi7r50kxj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-heart-engrave" /></template>
