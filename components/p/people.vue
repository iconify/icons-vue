<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/m_ccj3bub.css';
import '../../css/z/zqmr3vbur.css';
import '../../css/y/yx14sebtn.css';
import '../../css/q/qw60vmbud.css';
import '../../css/d/den2n8sxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="m_ccj3bub"/><path class="zqmr3vbur"/><path class="yx14sebtn"/><path class="qw60vmbud"/><path class="den2n8sxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:people" /></template>
