<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tyc3wod7f.css';
import '../../css/b/bn-fczxak.css';
import '../../css/u/uc23p5bxt.css';
import '../../css/l/lwtwrjtki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tyc3wod7f wm-k"/><path class="bn-fczxak wm-a"/><path class="uc23p5bxt wm-k"/><path class="lwtwrjtki wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rainbow-sketch" /></template>
