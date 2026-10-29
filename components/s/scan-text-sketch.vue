<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l8807ublx.css';
import '../../css/f/f91jueh9c.css';
import '../../css/l/lzvbhobgb.css';
import '../../css/i/i-xuwwzrm.css';
import '../../css/r/rxw6t9p2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l8807ublx"/><path class="f91jueh9c wm-k"/><path class="lzvbhobgb wm-a"/><path class="i-xuwwzrm wm-k"/><path class="rxw6t9p2o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-text-sketch" /></template>
