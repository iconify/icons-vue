<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rqhbxpmil.css';
import '../../css/s/sd6unnbbl.css';
import '../../css/f/f7sc4du7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rqhbxpmil"/><path class="sd6unnbbl wm-k"/><path class="f7sc4du7o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toran-sketch" /></template>
