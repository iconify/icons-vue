<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ekmb91bny.css';
import '../../css/h/hzem-r0io.css';
import '../../css/f/f6fjwablo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="ekmb91bny"/><circle class="hzem-r0io"/><path class="f6fjwablo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:stethoscope" /></template>
