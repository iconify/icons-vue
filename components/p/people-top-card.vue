<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/clsvsg_8u.css';
import '../../css/d/dlwj5t8ym.css';
import '../../css/n/nzi04mbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="clsvsg_8u"/><circle class="dlwj5t8ym"/><path class="nzi04mbzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:people-top-card" /></template>
