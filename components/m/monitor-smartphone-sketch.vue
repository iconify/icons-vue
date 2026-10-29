<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hg6i1ab2w.css';
import '../../css/d/d3kxx1b4n.css';
import '../../css/t/t36yflbru.css';
import '../../css/d/dkml2cbdk.css';
import '../../css/n/nv7sulbkq.css';
import '../../css/a/a_85qab1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hg6i1ab2w wm-s"/><path class="d3kxx1b4n wm-k"/><path class="t36yflbru wm-k"/><path class="dkml2cbdk wm-a"/><path class="nv7sulbkq wm-s"/><path class="a_85qab1n wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-smartphone-sketch" /></template>
