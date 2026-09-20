<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dc-opbbnk.css';
import '../../css/f/fqnkg2bwc.css';
import '../../css/f/f99jusbwg.css';
import '../../css/o/o6n94jakv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dc-opbbnk"/><path class="fqnkg2bwc"/><path class="f99jusbwg"/><path class="o6n94jakv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:server-hand" /></template>
