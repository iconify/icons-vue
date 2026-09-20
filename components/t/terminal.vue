<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/d/dn_xbcb7g.css';
import '../../css/g/g9ew6e1fs.css';
import '../../css/p/ppsbne-ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="dn_xbcb7g"/><path class="g9ew6e1fs"/><path class="ppsbne-ws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:terminal" /></template>
