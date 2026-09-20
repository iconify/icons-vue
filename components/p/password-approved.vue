<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v_91i9b8y.css';
import '../../css/h/h2ye-xbav.css';
import '../../css/t/t24s_tb_v.css';
import '../../css/y/ytvj_nbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v_91i9b8y"/><path class="h2ye-xbav"/><path class="t24s_tb_v"/><path class="ytvj_nbgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:password-approved" /></template>
