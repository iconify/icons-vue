<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jjfywviqd.css';
import '../../css/c/csm3i_bhj.css';
import '../../css/d/d58u2t8ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jjfywviqd"/><path class="csm3i_bhj"/><path class="d58u2t8ks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:presentation-projector-screen-budget-analytics" /></template>
