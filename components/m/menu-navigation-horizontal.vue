<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w8ab97v2n.css';
import '../../css/k/kcvvg0a8o.css';
import '../../css/k/kkgxl-zeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w8ab97v2n"/><path class="kcvvg0a8o"/><path class="kkgxl-zeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:menu-navigation-horizontal" /></template>
