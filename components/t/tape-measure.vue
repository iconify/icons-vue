<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/onvwtm0bf.css';
import '../../css/x/x-0x3eb3f.css';
import '../../css/m/m-j0d04lz.css';
import '../../css/b/bukp5cceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="onvwtm0bf"/><path class="x-0x3eb3f"/><circle class="m-j0d04lz"/><path class="bukp5cceq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:tape-measure" /></template>
