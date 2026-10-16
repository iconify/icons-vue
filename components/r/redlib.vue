<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqu2_e4mu.css';
import '../../css/x/xqvmvkbpa.css';
import '../../css/g/g-eromb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g transform="matrix(1 0 0 -1 0 512)"><circle class="pqu2_e4mu"/><path class="xqvmvkbpa"/><path class="g-eromb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:redlib" /></template>
