<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b2vlpabdt.css';
import '../../css/o/oi7bi6bzv.css';
import '../../css/c/cc61p4bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b2vlpabdt"/><path class="oi7bi6bzv"/><path class="cc61p4bvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:multimedia-controls-single-track" /></template>
