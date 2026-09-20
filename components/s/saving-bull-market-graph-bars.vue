<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nht91tbvp.css';
import '../../css/z/zk_sql93n.css';
import '../../css/u/u2f-v0b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nht91tbvp"/><path class="zk_sql93n"/><path class="u2f-v0b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:saving-bull-market-graph-bars" /></template>
