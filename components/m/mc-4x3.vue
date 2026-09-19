<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/z/zn_b-0bsk.css';
import '../../css/e/ee3n-ybbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="zn_b-0bsk"/><path class="ee3n-ybbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mc-4x3" /></template>
