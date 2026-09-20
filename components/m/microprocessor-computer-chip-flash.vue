<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i-k9h4bzq.css';
import '../../css/u/u64mz0bwh.css';
import '../../css/f/fyhqbw9pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i-k9h4bzq"/><path class="u64mz0bwh"/><path class="fyhqbw9pi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:microprocessor-computer-chip-flash" /></template>
