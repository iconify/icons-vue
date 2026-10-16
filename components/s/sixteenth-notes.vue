<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hdgv94bgu.css';
import '../../css/d/dqapyabwu.css';
import '../../css/t/tke4h5b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hdgv94bgu"/><circle class="dqapyabwu"/><circle class="tke4h5b0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sixteenth-notes" /></template>
