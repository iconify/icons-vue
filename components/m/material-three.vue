<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/ty8l4nl8s.css';
import '../../css/y/yi7ddnb4w.css';
import '../../css/p/pr05wzb5d.css';
import '../../css/t/thdjtvtxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ty8l4nl8s"/><path class="yi7ddnb4w"/><path clip-rule="evenodd" class="pr05wzb5d"/><path class="thdjtvtxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:material-three" /></template>
