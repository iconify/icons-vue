<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sezfl3bth.css';
import '../../css/g/gdt76bcot.css';
import '../../css/r/r4tzj-bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sezfl3bth"/><path class="gdt76bcot"/><path class="r4tzj-bic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-business-card" /></template>
