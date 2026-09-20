<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jog7wibwp.css';
import '../../css/w/wx_6pkbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jog7wibwp"/><path class="wx_6pkbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-square" /></template>
