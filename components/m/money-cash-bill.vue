<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vchse2bmr.css';
import '../../css/n/n7oztbbat.css';
import '../../css/e/ebzbuu97s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vchse2bmr"/><path class="n7oztbbat"/><path class="ebzbuu97s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:money-cash-bill" /></template>
