<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bz-6vcbqb.css';
import '../../css/p/pylfr_bqw.css';
import '../../css/a/axd7xdr2n.css';
import '../../css/w/wmrlzwbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bz-6vcbqb"/><path class="pylfr_bqw wm-a"/><path class="axd7xdr2n wm-k"/><path class="wm-a wmrlzwbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-camera-sketch" /></template>
