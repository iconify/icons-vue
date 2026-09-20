<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xzi62pqbj.css';
import '../../css/h/hmocrmbht.css';
import '../../css/a/am_q_ho_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xzi62pqbj"/><path class="hmocrmbht"/><path class="am_q_ho_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:money-coin-stack" /></template>
