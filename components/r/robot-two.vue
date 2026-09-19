<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/v/vp82i6bmg.css';
import '../../css/w/wbev7pbna.css';
import '../../css/a/amfmd727l.css';
import '../../css/f/fkv52firo.css';
import '../../css/e/eia4hzbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="vp82i6bmg"/><path class="wbev7pbna"/><circle class="amfmd727l"/><path class="fkv52firo"/><path class="eia4hzbco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:robot-two" /></template>
