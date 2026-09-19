<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tq71b84bu.css';
import '../../css/j/jr20aub9c.css';
import '../../css/m/m5ixigb2w.css';
import '../../css/x/xuu65oubr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tq71b84bu"/><path class="jr20aub9c"/><path class="m5ixigb2w"/><path class="xuu65oubr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:vc" /></template>
