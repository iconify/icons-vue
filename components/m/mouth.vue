<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsphsoupa.css';
import '../../css/w/w255u2bzb.css';
import '../../css/l/lazshccld.css';
import '../../css/d/d1ycr9k0j.css';
import '../../css/n/nra_qptzd.css';
import '../../css/f/fe99xmb9g.css';
import '../../css/f/f81rhhb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGA8AHrdcU" class="wsphsoupa"/></defs><path class="w255u2bzb"/><use href="#SVGA8AHrdcU"/><use href="#SVGA8AHrdcU"/><g class="lazshccld"><path class="d1ycr9k0j"/><path class="nra_qptzd"/><path class="fe99xmb9g"/><path class="f81rhhb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mouth" /></template>
