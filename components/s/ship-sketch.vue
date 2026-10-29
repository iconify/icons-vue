<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kfpn-obso.css';
import '../../css/h/h_2mi-a_x.css';
import '../../css/p/puw94sbom.css';
import '../../css/u/uxhs8ejfg.css';
import '../../css/d/diio2jb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kfpn-obso"/><path class="h_2mi-a_x wm-k"/><path class="puw94sbom wm-a"/><path class="uxhs8ejfg wm-k"/><path class="diio2jb3f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ship-sketch" /></template>
