<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/v9jvlqb3d.css';
import '../../css/l/la-dqtbxo.css';
import '../../css/l/lx86l0pzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="v9jvlqb3d"/><rect class="la-dqtbxo"/><path class="lx86l0pzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:newlybuild" /></template>
