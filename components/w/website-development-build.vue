<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nvof7u14j.css';
import '../../css/m/mbpy3bcwa.css';
import '../../css/l/l3fsfkbua.css';
import '../../css/m/mufjy7bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nvof7u14j"/><path class="mbpy3bcwa"/><path class="l3fsfkbua"/><path class="mufjy7bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:website-development-build" /></template>
