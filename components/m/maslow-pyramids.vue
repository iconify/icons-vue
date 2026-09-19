<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/peboz8bop.css';
import '../../css/g/g0t_6qahn.css';
import '../../css/f/frmm1dwzb.css';
import '../../css/i/ismxphoxz.css';
import '../../css/g/g5rj52b6j.css';
import '../../css/o/op7tkue1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="peboz8bop"/><path class="g0t_6qahn"/><path class="frmm1dwzb"/><path class="ismxphoxz"/><path class="g5rj52b6j"/><path class="op7tkue1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:maslow-pyramids" /></template>
