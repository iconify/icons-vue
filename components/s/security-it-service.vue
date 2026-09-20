<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e05xtxd5b.css';
import '../../css/k/krxcl4xgx.css';
import '../../css/z/zps3a9brs.css';
import '../../css/g/gr3pn8_ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e05xtxd5b"/><path class="krxcl4xgx"/><path class="zps3a9brs"/><path class="gr3pn8_ar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:security-it-service" /></template>
