<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/h/hma-isu1d.css';
import '../../css/d/dnokfxkrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="hma-isu1d"/><path class="dnokfxkrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ua-4x3" /></template>
