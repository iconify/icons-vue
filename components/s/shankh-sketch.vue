<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/imu2sccys.css';
import '../../css/b/bmd3pgbof.css';
import '../../css/a/a6lt9wbyk.css';
import '../../css/l/lm4f5pb4c.css';
import '../../css/a/aejpc4hlz.css';
import '../../css/j/jp6-iyb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="imu2sccys"/><path class="bmd3pgbof wm-k"/><path class="a6lt9wbyk wm-k"/><path class="lm4f5pb4c wm-a"/><path class="aejpc4hlz wm-a"/><path class="jp6-iyb4f wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shankh-sketch" /></template>
