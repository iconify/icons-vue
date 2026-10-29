<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/asn38kb9q.css';
import '../../css/u/u4d-mh8hw.css';
import '../../css/g/gqr-fjz3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="asn38kb9q"/><path class="u4d-mh8hw wm-shadow"/><path class="gqr-fjz3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-dashed-engrave" /></template>
