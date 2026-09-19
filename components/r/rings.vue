<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dpzbtra.css';
import '../../css/w/ws8lrmlgs.css';
import '../../css/h/hs1eo5b-l.css';
import '../../css/b/bqv7lzboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="ws8lrmlgs"/><path class="hs1eo5b-l"/><path class="bqv7lzboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rings" /></template>
