<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xs4al_e6r.css';
import '../../css/v/vj3558bmh.css';
import '../../css/j/jdwknqbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xs4al_e6r"/><path class="vj3558bmh"/><path class="jdwknqbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-sketch" /></template>
