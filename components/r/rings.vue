<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dpzbtra.css';
import '../../css/c/cf7ta6bqc.css';
import '../../css/p/pbc9w196e.css';
import '../../css/h/hs1eo5b-l.css';
import '../../css/b/bqv7lzboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="cf7ta6bqc"/><path class="pbc9w196e"/><path class="hs1eo5b-l"/><path class="bqv7lzboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:rings" /></template>
