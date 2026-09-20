<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/llmotgtmg.css';
import '../../css/j/j_cmhzgyl.css';
import '../../css/d/ddso4ebsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="llmotgtmg"/><path class="j_cmhzgyl"/><path class="ddso4ebsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:modern-payment-contactless" /></template>
