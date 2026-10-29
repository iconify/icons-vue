<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hgykuurez.css';
import '../../css/w/w18n-2bbj.css';
import '../../css/e/eojrhrb4s.css';
import '../../css/m/manj_xg0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hgykuurez wm-k"/><path class="w18n-2bbj wm-a"/><path class="eojrhrb4s wm-k"/><path class="manj_xg0q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:motorcycle-sketch" /></template>
