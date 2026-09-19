<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wb3mwmbun.css';
import '../../css/z/zp7rzkbkq.css';
import '../../css/g/gde01rm7l.css';
import '../../css/y/yruw9vbqy.css';
import '../../css/s/s029glbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="wb3mwmbun"/><path class="zp7rzkbkq"/><path class="gde01rm7l"/><path class="yruw9vbqy"/><path class="s029glbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:topic" /></template>
