<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gev3iobdk.css';
import '../../css/r/r0lcoh1hs.css';
import '../../css/l/l_usi832h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gev3iobdk"/><path class="r0lcoh1hs wm-k"/><path class="l_usi832h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volleyball-sketch" /></template>
