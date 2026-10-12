<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/ppcynk1aj.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/s/s6te4phsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ppcynk1aj"/><path class="s1a2eew1e"/><path class="s6te4phsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-down-left-duotone" /></template>
