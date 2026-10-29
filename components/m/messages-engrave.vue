<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sdh991bhr.css';
import '../../css/g/g1iev7bns.css';
import '../../css/p/p4mssnb1f.css';
import '../../css/e/e1arevqad.css';
import '../../css/l/lnuv79fzi.css';
import '../../css/m/m50p1qb4g.css';
import '../../css/x/x4mio0oxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sdh991bhr wm-k"/><path class="g1iev7bns wm-a"/><path class="p4mssnb1f wm-a"/><path class="e1arevqad wm-k"/><path class="lnuv79fzi wm-shadow"/><path class="m50p1qb4g wm-k"/><path class="wm-a x4mio0oxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:messages-engrave" /></template>
