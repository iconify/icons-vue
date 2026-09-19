<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5cg8fb9r.css';
import '../../css/q/qgymvr2-d.css';
import '../../css/y/ytep3bcxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="qgymvr2-d"/><path class="ytep3bcxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:thin" /></template>
