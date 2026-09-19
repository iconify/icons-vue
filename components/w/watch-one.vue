<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m-2wupbos.css';
import '../../css/q/q7g5sf5wm.css';
import '../../css/w/we227k77z.css';
import '../../css/v/vy66crryu.css';
import '../../css/j/jiaa8rnkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="m-2wupbos"/><path class="q7g5sf5wm"/><circle class="we227k77z"/><path class="vy66crryu"/><path class="jiaa8rnkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:watch-one" /></template>
