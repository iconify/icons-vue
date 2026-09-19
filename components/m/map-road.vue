<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/f0ucseb7n.css';
import '../../css/k/k4o9dxbnn.css';
import '../../css/t/tnvxvpsdk.css';
import '../../css/t/t_4e_wtts.css';
import '../../css/w/wjc26y0iw.css';
import '../../css/l/l_cwwybbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="f0ucseb7n"/><path class="k4o9dxbnn"/><path class="tnvxvpsdk"/><path class="t_4e_wtts"/><path class="wjc26y0iw"/><path class="l_cwwybbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:map-road" /></template>
