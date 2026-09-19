<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/kjic1aczr.css';
import '../../css/e/e6pm4obja.css';
import '../../css/l/lume5fb4x.css';
import '../../css/m/m5rmsl-7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="kjic1aczr"/><path class="e6pm4obja"/><path class="lume5fb4x"/><path class="m5rmsl-7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:petrol" /></template>
