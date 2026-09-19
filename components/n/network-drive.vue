<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/idtbkobxl.css';
import '../../css/t/tfx552bzo.css';
import '../../css/w/wfaf1ggge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="idtbkobxl"/><path class="tfx552bzo"/><path class="wfaf1ggge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:network-drive" /></template>
