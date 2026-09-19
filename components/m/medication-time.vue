<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/pg5rmbcty.css';
import '../../css/q/qz-mrebrm.css';
import '../../css/t/tgxo-cukz.css';
import '../../css/w/w7__z0ipt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="pg5rmbcty"/><path class="qz-mrebrm"/><circle class="tgxo-cukz"/><path class="w7__z0ipt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:medication-time" /></template>
