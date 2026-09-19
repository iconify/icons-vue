<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/o/ouk324llz.css';
import '../../css/y/yfm2a_b8o.css';
import '../../css/l/lkfh1obyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="ouk324llz"/><path class="yfm2a_b8o"/><path class="lkfh1obyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:right-bar" /></template>
