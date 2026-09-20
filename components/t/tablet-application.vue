<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xx8uc8bgh.css';
import '../../css/j/jvgwolb2i.css';
import '../../css/m/maqr8cuyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xx8uc8bgh"/><path class="jvgwolb2i"/><path class="maqr8cuyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:tablet-application" /></template>
