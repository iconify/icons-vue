<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q7cmimb1r.css';
import '../../css/r/rq8m0xmwq.css';
import '../../css/c/cb4dv35kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q7cmimb1r"/><path class="rq8m0xmwq"/><path class="cb4dv35kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:task-list-clipboard-favorite-star" /></template>
