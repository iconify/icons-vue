<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/ixbkhldpp.css';
import '../../css/l/lchlphbxu.css';
import '../../css/p/pv42_gb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ixbkhldpp"/><path class="lchlphbxu"/><path class="pv42_gb1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:toilet" /></template>
