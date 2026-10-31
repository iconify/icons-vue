<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ug4ve3gnj.css';
import '../../css/f/f6-d95u-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="ug4ve3gnj"/><path class="f6-d95u-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:so" /></template>
