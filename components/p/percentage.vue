<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cc4k4-b0i.css';
import '../../css/c/c45-6cbdn.css';
import '../../css/o/opakkwbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="cc4k4-b0i"/><circle class="c45-6cbdn"/><path class="opakkwbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:percentage" /></template>
