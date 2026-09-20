<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o9_yfztdo.css';
import '../../css/n/nkgvlpo6l.css';
import '../../css/b/bjr3rwbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o9_yfztdo"/><path class="nkgvlpo6l"/><path class="bjr3rwbuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:website-development-monitor-www-web" /></template>
