<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fsxwks63x.css';
import '../../css/s/sep7-euwy.css';
import '../../css/y/y5ye8hb2g.css';
import '../../css/g/ghup45byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fsxwks63x"/><path class="sep7-euwy"/><path class="y5ye8hb2g"/><path class="ghup45byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:meeting-presentation" /></template>
