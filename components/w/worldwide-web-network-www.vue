<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xq_ez15tr.css';
import '../../css/x/xrw5hkbia.css';
import '../../css/z/zra8kbb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xq_ez15tr"/><path class="xrw5hkbia"/><path class="zra8kbb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:worldwide-web-network-www" /></template>
