<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xrv5j_bub.css';
import '../../css/s/sgsm6fbfm.css';
import '../../css/k/kuf581b4z.css';
import '../../css/z/zvyd9gb3i.css';
import '../../css/f/fvt8f3b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xrv5j_bub"/><path class="sgsm6fbfm wm-k"/><path class="kuf581b4z wm-a"/><path class="wm-k zvyd9gb3i"/><path class="fvt8f3b6b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wand-sketch" /></template>
