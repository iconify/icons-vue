<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sqm5gsvzg.css';
import '../../css/d/dcda15btx.css';
import '../../css/a/amul4stfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sqm5gsvzg"/><path class="dcda15btx"/><path class="amul4stfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:task-list-clipboard-share" /></template>
