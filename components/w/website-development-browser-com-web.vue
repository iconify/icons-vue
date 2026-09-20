<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vw_gxpbld.css';
import '../../css/t/t0ujf-b5o.css';
import '../../css/u/u_ntt4bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vw_gxpbld"/><path class="t0ujf-b5o"/><path class="u_ntt4bqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:website-development-browser-com-web" /></template>
