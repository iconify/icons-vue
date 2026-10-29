<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y08lrpbvo.css';
import '../../css/i/ihus8nt9r.css';
import '../../css/d/dpl7m5bka.css';
import '../../css/p/pfgi2nbvf.css';
import '../../css/w/wrc723bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y08lrpbvo"/><path class="ihus8nt9r wm-a"/><path class="dpl7m5bka wm-shadow"/><path class="pfgi2nbvf wm-k"/><path class="wm-a wrc723bxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ungroup-engrave" /></template>
