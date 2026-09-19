<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/ip3i1kbac.css';
import '../../css/b/b1c1gxmof.css';
import '../../css/w/wojuw_vqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ip3i1kbac"/><path class="b1c1gxmof"/><path class="wojuw_vqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:scallion" /></template>
