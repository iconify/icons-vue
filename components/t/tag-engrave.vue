<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pnk4cfbhi.css';
import '../../css/s/s7iqi01xc.css';
import '../../css/d/dyl9j_8su.css';
import '../../css/e/e61c4pwgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pnk4cfbhi wm-k"/><path class="s7iqi01xc wm-shadow"/><path class="dyl9j_8su wm-k"/><path class="e61c4pwgm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tag-engrave" /></template>
