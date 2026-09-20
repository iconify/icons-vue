<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sb8lcabgc.css';
import '../../css/c/c-hho8xra.css';
import '../../css/o/ow1qj4p-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sb8lcabgc"/><path class="c-hho8xra"/><path class="ow1qj4p-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:programming-language-bookmark-javascript" /></template>
