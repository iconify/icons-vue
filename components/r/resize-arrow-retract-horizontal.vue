<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w70lsgs8c.css';
import '../../css/w/wokny8d9v.css';
import '../../css/a/a5wgy1bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="w70lsgs8c"><path class="wokny8d9v"/><path class="a5wgy1bzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:resize-arrow-retract-horizontal" /></template>
