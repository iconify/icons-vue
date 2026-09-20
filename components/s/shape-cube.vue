<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b_kv34bwu.css';
import '../../css/v/vbno8kv6y.css';
import '../../css/h/hsnp8gqct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b_kv34bwu"/><path class="vbno8kv6y"/><path class="hsnp8gqct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shape-cube" /></template>
