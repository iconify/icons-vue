<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bnk-_vbtx.css';
import '../../css/l/lsec2j3xn.css';
import '../../css/w/w9x8kzbyj.css';
import '../../css/v/v1_9a1bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bnk-_vbtx"/><path class="lsec2j3xn"/><path class="w9x8kzbyj"/><path class="v1_9a1bkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:reel" /></template>
