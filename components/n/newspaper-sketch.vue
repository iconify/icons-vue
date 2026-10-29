<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ex2o_-t6b.css';
import '../../css/u/u1azafbba.css';
import '../../css/h/hxppdibgb.css';
import '../../css/o/oapjrnbtk.css';
import '../../css/s/sn3o9xbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ex2o_-t6b"/><path class="u1azafbba wm-k"/><path class="hxppdibgb wm-a"/><path class="oapjrnbtk wm-k"/><path class="sn3o9xbjr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:newspaper-sketch" /></template>
