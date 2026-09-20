<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x9xer61ny.css';
import '../../css/d/dp0zwgbbl.css';
import '../../css/w/wuyzb9bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x9xer61ny"/><path class="dp0zwgbbl"/><path class="wuyzb9bxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:transfer-pictures-smartphone" /></template>
