<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hmzy87vxc.css';
import '../../css/s/sif8embcq.css';
import '../../css/j/jft-c8bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hmzy87vxc"/><path class="sif8embcq"/><path class="jft-c8bfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:products-purse" /></template>
