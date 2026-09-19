<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/f/fagbf2b8f.css';
import '../../css/x/x0yq8fapu.css';
import '../../css/r/r1o46bcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="fagbf2b8f"/><path class="x0yq8fapu"/><path class="r1o46bcgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shop" /></template>
