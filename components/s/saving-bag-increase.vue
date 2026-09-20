<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sbto5_u1s.css';
import '../../css/d/daz3bxb2w.css';
import '../../css/t/tj-_z79bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sbto5_u1s"/><path class="daz3bxb2w"/><path class="tj-_z79bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:saving-bag-increase" /></template>
