<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nq7gakb6c.css';
import '../../css/b/bvsehuhap.css';
import '../../css/d/dfv0w4p5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nq7gakb6c"/><path class="bvsehuhap"/><path class="dfv0w4p5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:transform-right" /></template>
