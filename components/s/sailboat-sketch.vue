<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ip5s8tb9t.css';
import '../../css/l/l7_1lub0r.css';
import '../../css/h/h51zevb-k.css';
import '../../css/z/zn50j-g9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ip5s8tb9t wm-k"/><path class="l7_1lub0r wm-a"/><path class="h51zevb-k wm-k"/><path class="wm-a zn50j-g9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sailboat-sketch" /></template>
