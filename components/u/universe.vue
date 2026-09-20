<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n5g3q8bii.css';
import '../../css/n/ned4scb6o.css';
import '../../css/o/ohvlkxycg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5g3q8bii"/><path class="ned4scb6o"/><path class="ohvlkxycg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:universe" /></template>
