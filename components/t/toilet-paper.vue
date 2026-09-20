<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tmcd2b_ry.css';
import '../../css/h/h-yvp4bkp.css';
import '../../css/s/spj6lnxch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tmcd2b_ry"/><path class="h-yvp4bkp"/><path class="spj6lnxch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:toilet-paper" /></template>
