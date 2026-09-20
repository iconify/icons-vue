<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v6thdh7bf.css';
import '../../css/p/pj5v24aaj.css';
import '../../css/f/fiihxccoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v6thdh7bf"/><path class="pj5v24aaj"/><path class="fiihxccoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:playlist-album-1" /></template>
