<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vdlg8tffb.css';
import '../../css/u/ulof31eud.css';
import '../../css/q/quyrsobnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vdlg8tffb"/><path class="ulof31eud"/><path class="quyrsobnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:note-remove-filled" /></template>
