<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/u85aeivei.css';
import '../../css/m/m-7170blj.css';
import '../../css/b/btdqlqbzk.css';
import '../../css/b/bka8n3bzg.css';
import '../../css/m/mitcfcb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="u85aeivei"/><path class="m-7170blj"/><path class="btdqlqbzk"/><path class="bka8n3bzg"/><path class="mitcfcb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:ui-webpage-bullets" /></template>
