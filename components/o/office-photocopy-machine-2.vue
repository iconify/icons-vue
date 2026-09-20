<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hzpxzpblh.css';
import '../../css/c/cb_ci4bjj.css';
import '../../css/m/mfdfogbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hzpxzpblh"/><path class="cb_ci4bjj"/><path class="mfdfogbom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-photocopy-machine-2" /></template>
