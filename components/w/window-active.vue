<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/q-vpvrb_t.css';
import '../../css/f/fz2y-m-od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="q-vpvrb_t"/><path class="fz2y-m-od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:window-active" /></template>
