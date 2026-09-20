<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bgm_-y5gj.css';
import '../../css/v/vmtis9bmr.css';
import '../../css/j/jx7exii8n.css';
import '../../css/b/b25i71vqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bgm_-y5gj"/><path class="vmtis9bmr"/><path class="jx7exii8n"/><path class="b25i71vqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wifi-on" /></template>
