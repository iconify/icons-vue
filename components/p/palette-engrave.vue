<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lu8lw__kt.css';
import '../../css/k/kgl-ptb4u.css';
import '../../css/h/hdzvs592w.css';
import '../../css/o/or693yu9a.css';
import '../../css/r/r-tfq900y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lu8lw__kt wm-k"/><path class="kgl-ptb4u wm-a"/><path class="hdzvs592w wm-shadow"/><path class="or693yu9a wm-k"/><path class="r-tfq900y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palette-engrave" /></template>
