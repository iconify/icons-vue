<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xmgj-ltpl.css';
import '../../css/m/mp9eqybsi.css';
import '../../css/c/c0-nyjt-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xmgj-ltpl"/><path class="mp9eqybsi"/><path class="c0-nyjt-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:volume-control-medium-1" /></template>
