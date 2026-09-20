<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rgcigdc_c.css';
import '../../css/p/p0r1koben.css';
import '../../css/k/ke2-dkbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rgcigdc_c"/><path class="p0r1koben"/><path class="ke2-dkbvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:text-formating-rotate-angle" /></template>
