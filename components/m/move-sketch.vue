<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/ddoztfbry.css';
import '../../css/f/ftse9tv2o.css';
import '../../css/n/nuri-pjqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ddoztfbry wm-k"/><path class="ftse9tv2o wm-k"/><path class="nuri-pjqg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:move-sketch" /></template>
