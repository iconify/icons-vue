<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/m/mqowuqbjp.css';
import '../../css/z/zf6nr4d2o.css';
import '../../css/g/g0v9dsb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="mqowuqbjp"/><path class="zf6nr4d2o"/><circle class="g0v9dsb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:u-turn-left" /></template>
