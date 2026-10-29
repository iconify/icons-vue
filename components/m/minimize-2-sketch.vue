<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r72-5pblm.css';
import '../../css/n/n0rfpxv8v.css';
import '../../css/u/uera-ebmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r72-5pblm wm-k"/><path class="n0rfpxv8v wm-k"/><path class="uera-ebmf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-2-sketch" /></template>
