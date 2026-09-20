<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sz9k32bqj.css';
import '../../css/o/ot5asko0x.css';
import '../../css/d/d3kganbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sz9k32bqj"/><path class="ot5asko0x"/><path class="d3kganbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-tape-2" /></template>
