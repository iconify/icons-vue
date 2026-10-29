<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ocujuybcd.css';
import '../../css/y/yfukz_bfm.css';
import '../../css/q/qt7btobjz.css';
import '../../css/m/m3r3og_wj.css';
import '../../css/g/g_59g7p8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ocujuybcd"/><path class="wm-k yfukz_bfm"/><path class="qt7btobjz wm-a"/><path class="m3r3og_wj wm-k"/><path class="g_59g7p8z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:school-sketch" /></template>
