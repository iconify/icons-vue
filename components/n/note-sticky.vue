<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lxxtlbu8s.css';
import '../../css/w/wii78dxzz.css';
import '../../css/m/m5u67xvhu.css';
import '../../css/p/pe-9v_bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lxxtlbu8s"/><path class="wii78dxzz"/><path class="m5u67xvhu"/><path class="pe-9v_bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:note-sticky" /></template>
