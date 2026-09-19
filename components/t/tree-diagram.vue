<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/qyszsvcyl.css';
import '../../css/y/yrbyiib0t.css';
import '../../css/i/iass40n0e.css';
import '../../css/j/jz89wkdin.css';
import '../../css/w/ww5-o3blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="qyszsvcyl"/><circle class="yrbyiib0t"/><circle class="iass40n0e"/><circle class="jz89wkdin"/><path class="ww5-o3blo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tree-diagram" /></template>
