<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/w/w7y2_zn0h.css';
import '../../css/o/oeuerccbj.css';
import '../../css/o/olhj8txmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="matrix(0 1 1 0 2.5 2.5)" class="jtowsomii"><path class="w7y2_zn0h"/><circle class="oeuerccbj"/><path class="olhj8txmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:reset-temporary" /></template>
