<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hc8pcsbjm.css';
import '../../css/c/cmtd2kblp.css';
import '../../css/k/k9pcsy82o.css';
import '../../css/v/vdtfczwsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="hc8pcsbjm"/><path class="cmtd2kblp"/><path clip-rule="evenodd" class="k9pcsy82o"/><path class="vdtfczwsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:monitor-camera" /></template>
