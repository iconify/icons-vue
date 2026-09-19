<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/ezq3zxkis.css';
import '../../css/e/e_xfgzbtb.css';
import '../../css/m/mv7_v6hps.css';
import '../../css/q/q8f8vcygc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ezq3zxkis"/><path clip-rule="evenodd" class="e_xfgzbtb"/><path class="mv7_v6hps"/><path class="q8f8vcygc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:microscope" /></template>
