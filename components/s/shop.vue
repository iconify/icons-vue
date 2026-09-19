<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/prvg-xbay.css';
import '../../css/x/x0yq8fapu.css';
import '../../css/n/ny1ve4bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="prvg-xbay"/><path class="x0yq8fapu"/><path class="ny1ve4bvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:shop" /></template>
