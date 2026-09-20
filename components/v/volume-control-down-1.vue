<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b4jwp893i.css';
import '../../css/m/mz8zz6b9f.css';
import '../../css/b/bu8aiwuof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b4jwp893i"/><path class="mz8zz6b9f"/><path class="bu8aiwuof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:volume-control-down-1" /></template>
