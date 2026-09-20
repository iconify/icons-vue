<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p907x47-t.css';
import '../../css/n/n3xytbcmz.css';
import '../../css/b/bzh-1hb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p907x47-t"/><path class="n3xytbcmz"/><path class="bzh-1hb8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:optimization-graph-settings" /></template>
