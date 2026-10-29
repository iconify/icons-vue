<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z56fic-5s.css';
import '../../css/v/vg8lvr9zy.css';
import '../../css/s/smrkqr1kn.css';
import '../../css/g/gapblccgm.css';
import '../../css/d/d-i86qbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z56fic-5s"/><path class="vg8lvr9zy wm-a"/><path class="smrkqr1kn wm-shadow"/><path class="gapblccgm wm-k"/><path class="d-i86qbmd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sparkles-engrave" /></template>
