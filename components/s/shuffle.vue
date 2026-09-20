<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/iy3mnob7p.css';
import '../../css/e/e-qescbuo.css';
import '../../css/h/huu1r6ztb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="iy3mnob7p"/><path class="e-qescbuo"/><path class="huu1r6ztb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:shuffle" /></template>
