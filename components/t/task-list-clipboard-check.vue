<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dhv8f3bgq.css';
import '../../css/m/mb3ax-bwz.css';
import '../../css/m/m2---acsp.css';
import '../../css/a/aamj76buo.css';
import '../../css/r/rwkm9oblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dhv8f3bgq"/><path class="mb3ax-bwz"/><path class="m2---acsp"/><path class="aamj76buo"/><path class="rwkm9oblt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:task-list-clipboard-check" /></template>
