<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yb16dccix.css';
import '../../css/r/raay55lkn.css';
import '../../css/d/d826o74jr.css';
import '../../css/w/wgiyf7qtm.css';
import '../../css/i/i0m_0hbys.css';
import '../../css/m/murv6mteh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yb16dccix"/><path class="raay55lkn wm-a"/><path class="d826o74jr wm-s"/><path class="wgiyf7qtm wm-k"/><path class="i0m_0hbys wm-a"/><path class="murv6mteh wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:oven-sketch" /></template>
