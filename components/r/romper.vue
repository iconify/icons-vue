<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hfcnj25dk.css';
import '../../css/r/rg113dddb.css';
import '../../css/k/kj-k9st5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hfcnj25dk"/><path class="rg113dddb"/><path class="kj-k9st5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:romper" /></template>
