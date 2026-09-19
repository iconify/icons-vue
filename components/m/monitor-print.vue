<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zau_029ve.css';
import '../../css/d/ds0-m5bxn.css';
import '../../css/b/bej3h2bvr.css';
import '../../css/p/pw4dn1s2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="zau_029ve"/><path clip-rule="evenodd" class="ds0-m5bxn"/><path clip-rule="evenodd" class="bej3h2bvr"/><path class="pw4dn1s2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:monitor-print" /></template>
