<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yq7wqq0em.css';
import '../../css/c/c36ls8boi.css';
import '../../css/r/rsp9libtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yq7wqq0em"/><path class="c36ls8boi"/><path class="rsp9libtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:resize-expand-arrow" /></template>
