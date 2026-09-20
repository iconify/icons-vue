<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bznxcabtm.css';
import '../../css/n/nwp-27w7c.css';
import '../../css/h/h__ccyqjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bznxcabtm"/><path class="nwp-27w7c"/><path class="h__ccyqjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-basket-search" /></template>
