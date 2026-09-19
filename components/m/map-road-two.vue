<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/d70npacrz.css';
import '../../css/l/l8-q0ccsa.css';
import '../../css/k/k-3466b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="d70npacrz"/><path class="l8-q0ccsa"/><path class="k-3466b-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:map-road-two" /></template>
